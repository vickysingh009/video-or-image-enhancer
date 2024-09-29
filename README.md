# video-or-image-enhancer

# Create a Markdown file with only comparative images
markdown_content = """
# Super-Resolution Comparison Results

![result-edsr](docs/images/result-edsr.png)

![result-wdsr](docs/images/result-wdsr.png)

![result-srgan](docs/images/result-srgan.png)
"""

# Write the content to a Markdown file
with open('super_resolution_comparison.md', 'w') as f:
    f.write(markdown_content)

print("Markdown file created successfully!")
