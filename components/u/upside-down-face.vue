<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGszVs1Lmw" class="ki_znpbrx"/></defs><clipPath id="SVG5RzEidSo"><use href="#SVGszVs1Lmw"/></clipPath><g clip-path="url(#SVG5RzEidSo)"><path class="i3i91_iju"/></g><g clip-path="url(#SVG5RzEidSo)" class="ehej3-bmx"><path class="hr-u7rbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:upside-down-face" /></template>
<style>
.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.hr-u7rbnd {
  d: path("M42 82c-4.49.04-8.17-4.27-8.22-9.62c-.05-5.37 3.55-9.75 8.04-9.79c4.48-.04 8.17 4.27 8.22 9.64c.05 5.36-3.55 9.73-8.04 9.77m44.11 0c4.48-.01 8.11-4.36 8.1-9.71c-.01-5.37-3.66-9.7-8.14-9.69c-4.49.01-8.13 4.36-8.12 9.73c.02 5.35 3.67 9.68 8.16 9.67M63.89 30.94c-14.13 0-22.18 8.14-22.52 8.48a3.254 3.254 0 0 0 4.67 4.53c.25-.25 6.58-6.51 17.85-6.51s17.6 6.25 17.87 6.52a3.26 3.26 0 0 0 4.59.04a3.24 3.24 0 0 0 .06-4.58c-.34-.34-8.39-8.48-22.52-8.48");
}

.i3i91_iju {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M127.79 34.67c0-13.83-28.55-25.03-63.79-25.03C28.77 9.64.21 20.84.21 34.67S1.69 118.35 64 118.35c62.32.01 63.79-69.85 63.79-83.68");
}

.ki_znpbrx {
  d: path("M.41 0H128v128H.41z");
}

</style>
