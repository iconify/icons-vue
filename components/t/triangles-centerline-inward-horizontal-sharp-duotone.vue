<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ony6z4btl"/><path class="r_-4hoblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-inward-horizontal-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ony6z4btl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.057 14.73C12.299 14.79 12.687 14.97 12.829 15.18L17.053 21.44C17.259 21.75 17.279 22.14 17.106 22.47C16.932 22.8 16.593 23 16.224 23H7.777C7.408 23 7.067 22.8 6.894 22.47C6.721 22.14 6.742 21.75 6.948 21.44L11.26 15.05C11.399 14.95 11.887 14.75 12.057 14.73ZM16.224 1C16.593 1 16.932 1.2 17.106 1.53C17.279 1.86 17.259 2.25 17.053 2.56L12.829 8.82C12.667 9.06 12.338 9.22 12.054 9.26C11.722 9.26 11.358 9.09 11.172 8.82L6.948 2.56C6.742 2.25 6.721 1.86 6.894 1.53C7.067 1.2 7.408 1 7.777 1H16.224Z");
}

.r_-4hoblq {
  d: path("M23 11V13H1V11H23Z");
}

</style>
