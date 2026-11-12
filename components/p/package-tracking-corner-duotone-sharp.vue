<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vk_z-7bho"/><path class="o89ayfb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-tracking-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o89ayfb1z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v12h4M4 8l2-4h12l2 4M4 8h16m-3 8h.01M17 21c-2-2-4-4-4-5a4 4 0 1 1 8 0c0 1-2 3-4 5");
}

.vk_z-7bho {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.106 3.553A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4A1 1 0 0 1 20 9H4a1 1 0 0 1-.894-1.447Zm9.707 16.658a33 33 0 0 1-1.322-1.435C12.878 18.061 12 16.985 12 16a5 5 0 0 1 10 0c0 .985-.878 2.061-1.491 2.776q-.64.737-1.322 1.435c-.488.504-.984 1-1.48 1.496a1 1 0 0 1-1.414 0c-.496-.496-.992-.992-1.48-1.496");
}

</style>
