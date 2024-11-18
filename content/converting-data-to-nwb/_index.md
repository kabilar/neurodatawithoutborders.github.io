---
title: "Converting Data To NWB"

### List 
list:
    enable: true
    title: "Neurodata Without Borders (NWB) is a data standard for neurophysiology. Converting data to NWB involves:"
    items:
        - item: "Reading data and metadata from source files"
        - item: "Adding necessary metadata"
        - item: "Writing data and metadata to NWB following best practices"
        - item: "Packaging large datasets for optimal cloud deployment"
    content: "The NWB ecosystem offers various solutions, ranging from automated no-code tools to fine-grained programmatic options."

### Available Tools
available_tools_section:
    enable: true
    boxes: 
        - icon: "/images/nwb-guide.png"
          title: "NWB GUIDE (GUI for Data Entry)"
          type: "Downloadable application"
          features:
            - feature: "Guides users through data conversion process"
            - feature: "Supports 40+ common data formats"
            - feature: "Allows metadata entry"
            - feature: "Offers NWB file inspection via NWB Inspector"
            - feature: "Offers data visualization via Neurosift"
            - feature: "Facilitates uploading to DANDI Archive"
          limitations: "May require manual addition of lab-specific data"
          resources:
            - text: "Text Tutorial"
              link: /
            - text: "YouTube Walkthrough"
              link: /

        - icon: "/images/neuroconv.png"
          title: "NeuroConv"
          type: "Python library (underlies NWB GUIDE)"
          features:
            - feature: "Supports 44+ neurophysiology data formats"
            - feature: "Offers more flexibility than NWB GUIDE"
            - feature: "Provides tools for post-hoc time alignment of multiple data streams"
            - feature: "Supports cloud deployment"
          resources:
            - text: "GitHub Repository"
              link: /
            - text: "Documentation"
              link: /

        - icon: "/images/pynwb.png"
          title: "PyNWB"
          type: "Python library (underlies NeuroConv)"
          features:
            - feature: "Building NWB files from scratch"
            - feature: "Working with unsupported data formats"
            - feature: "Developing custom NWB extensions"
          resources:
            - text: "GitHub Repository"
              link: /
            - text: "Documentation"
              link: /
            - text: "Tutorials"
              link: /
            - text: "NWB YouTube Channel"
              link: /

        - icon: "/images/matnwb.png"
          title: "MatNWB"
          type: "MATLAB library"
          features:
            - feature: "Building NWB files from scratch"
            - feature: "Working with unsupported data formats"
          resources:
            - text: "GitHub Repository"
              link: /
            - text: "Tutorials"
              link: /
            - text: "NWB YouTube Channel"
              link: /

### Choosing Tools
choosing_tools:
    enable: true
    title: "Choosing the Right Tool"
    items:
        - item: "For most common data formats and straightforward conversions, start with NWB GUIDE."
        - item: "If you need more flexibility or are comfortable with Python, consider NeuroConv"
        - item: "For custom data formats, complex conversions, or when developing NWB extensions, use PyNWB or MatNWB."
    content: "Remember to consult the provided documentation and tutorials for detailed guidance on using each tool"
---