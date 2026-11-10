<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iiogawbmg"/><path clip-rule="evenodd" class="h3-21936o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parking-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h3-21936o {
  fill-rule: evenodd;
  d: path("M12 1C18.075 1 23 5.92 23 12C23 18.08 18.075 23 12 23C5.925 23 1 18.08 1 12C1 5.92 5.925 1 12 1ZM9.5 7C8.948 7 8.5 7.45 8.5 8V17H10.5V14H12C13.933 14 15.5 12.43 15.5 10.5C15.5 8.57 13.933 7 12 7H9.5Z");
}

.iiogawbmg {
  d: path("M12 9C12.828 9 13.5 9.67 13.5 10.5C13.5 11.33 12.828 12 12 12H10.5V9H12Z");
}

</style>
