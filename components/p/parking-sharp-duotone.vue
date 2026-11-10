<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qblrjuwrb"/><path clip-rule="evenodd" class="jg57diw9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parking-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jg57diw9h {
  fill-rule: evenodd;
  d: path("M12 7C13.933 7 15.5 8.57 15.5 10.5C15.5 12.43 13.933 14 12 14H10.5V17H8.5V8C8.5 7.45 8.948 7 9.5 7H12ZM10.5 12H12C12.828 12 13.5 11.33 13.5 10.5C13.5 9.67 12.828 9 12 9H10.5V12Z");
}

.qblrjuwrb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C18.075 1 23 5.92 23 12C23 18.08 18.075 23 12 23C5.925 23 1 18.08 1 12C1 5.92 5.925 1 12 1Z");
}

</style>
