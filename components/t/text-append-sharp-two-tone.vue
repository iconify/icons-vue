<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o9ym0n7sw"/><path clip-rule="evenodd" class="docjqyb4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-append-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.docjqyb4x {
  fill-rule: evenodd;
  d: path("M22 10H2V8H22V10ZM22 4H2V2H22V4ZM22 22H14V20H22V22ZM22 16H14V14H22V16Z");
}

.o9ym0n7sw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 17.75H8.471L7.6 16.93L8.968 15.47L11.684 18.02C11.885 18.21 12 18.47 12 18.75C12 19.03 11.885 19.29 11.684 19.48L8.995 22L7.628 20.54L8.472 19.75H3C2.448 19.75 2 19.3 2 18.75V14H4V17.75Z");
}

</style>
