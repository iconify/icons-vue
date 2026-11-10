<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="awnch8h2g"/><path clip-rule="evenodd" class="p-n3e0bko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-word-spacing-sharp-two-tone" /></template>
<style>
.awnch8h2g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 20V22H2V20H13Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p-n3e0bko {
  fill-rule: evenodd;
  d: path("M22 14V16H11V14H22ZM13 2V4H2V2H13ZM9 14V16H2V14H9ZM22 8V10H15V8H22ZM22 2V4H15V2H22ZM13 8V10H8V8H13ZM6 8V10H2V8H6Z");
}

</style>
