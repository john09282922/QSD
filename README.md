ECCV2024 Workshop paper (pending)

Title: QSD: Query-Selection Denoising score for Image Editing in Latent Diffusion Model

Abstract: With a surge in interest in diffusion models for image editing, textprompt interfaces such as Midjourney, DALL-E, and Stable Diffusion have been 
utilized. Recently, the Contrastive Denoising Score (CDS) method has emerged 
as a state-of-the-art among image-to-image translation diffusion models, leveraging both Delta Denoising Score (DDS) and contrastive loss based on Contrastive learning for Unpaired image-to-image Translation (CUT). However, CDS 
has the problem of preserving content from the original image. The object in the 
source image is not replaced by a user-intended query object, and the surrounding 
content seems to be not preserved well. We observed that the sources of the problem are from both the CUT method, which randomly selects features not related 
to query objects, and the DDS method not capturing structural details.
To address this issue, we propose the Query-Selection Denoising score using latent diffusion model (QSD). We employ query-selected attention maps to separate the object of interest from the rest of the image using contrastive learning 
and Latent Diffusion Model (LDM) under self-supervised learning to preserve 
the object’s structural shapes. Our proposed method demonstrates superior performance compared to other diffusion models in qualitative and quantitative evaluations while controlling the object and preserving other parts of the image
