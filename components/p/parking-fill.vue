<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pm636x3rn"/><path clip-rule="evenodd" class="adt5-1bho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parking-fill" /></template>
<style>
.adt5-1bho {
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.92 23 12C23 18.08 18.0751 23 12 23C5.9249 23 1 18.08 1 12C1 5.92 5.9249 1 12 1ZM10.5 7C9.3954 7 8.5 7.9 8.5 9V16C8.5 16.55 8.9477 17 9.5 17C10.0523 17 10.5 16.55 10.5 16V14H12C13.933 14 15.5 12.43 15.5 10.5C15.5 8.57 13.933 7 12 7H10.5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pm636x3rn {
  d: path("M12 9C12.8284 9 13.5 9.67 13.5 10.5C13.5 11.33 12.8284 12 12 12H10.5V9H12Z");
}

</style>
