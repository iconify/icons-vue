<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r8pwoubug"/><path clip-rule="evenodd" class="w93-6ibns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-insert-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r8pwoubug {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.684 4.52C11.885 4.71 12 4.97 12 5.25C12 5.53 11.885 5.79 11.684 5.98L8.968 8.53L7.6 7.07L8.471 6.25H4V10H2V5.25C2 4.7 2.448 4.25 3 4.25H8.472L7.628 3.46L8.995 2L11.684 4.52Z");
}

.w93-6ibns {
  fill-rule: evenodd;
  d: path("M22 22H2V20H22V22ZM22 16H2V14H22V16ZM22 10H14V8H22V10ZM22 4H14V2H22V4Z");
}

</style>
