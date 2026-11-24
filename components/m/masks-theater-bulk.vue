<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nvam7bbnf"/><path class="srpnfhbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:masks-theater-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nvam7bbnf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.091 11.842l-.868-4.924a3 3 0 0 1 2.433-3.476l5.909-1.041a3 3 0 0 1 3.476 2.433l.868 4.924a6.001 6.001 0 0 1-11.818 2.084");
}

.srpnfhbkw {
  d: path("M17.275 5.513h.01a1 1 0 0 1 0 2h-.01a1 1 0 1 1 0-2m-3.939.695h.01a1 1 0 0 1 0 2h-.01a1 1 0 0 1 0-2m-11.245 8.75l.868-4.924a3 3 0 0 1 3.476-2.433l1.264.223a.999.999 0 1 1-.347 1.969L6.087 9.57a1 1 0 0 0-1.158.811l-.868 4.924a3.999 3.999 0 0 0 6.87 3.418c.302-.323.547-.695.726-1.1a1 1 0 1 1 1.829.81a6 6 0 0 1-11.395-3.475m12.553-5.413a1.266 1.266 0 0 0 2.201-.387a1 1 0 1 1 1.902.62a3.268 3.268 0 0 1-5.677 1.001a1.001 1.001 0 0 1 1.574-1.234m-7.919 1.168h.01a1 1 0 0 1 0 2h-.01a1 1 0 1 1 0-2m-1.482 4.323a3.268 3.268 0 0 1 5.677 1.001a.997.997 0 0 1-1.028 1.307a1 1 0 0 1-.873-.686a1.267 1.267 0 0 0-2.201-.389a1.002 1.002 0 0 1-1.659-.125a1 1 0 0 1 .084-1.108");
}

</style>
