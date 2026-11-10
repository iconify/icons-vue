<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wob51cbxh"/><path class="kyhh7jbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-horizontal-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kyhh7jbsw {
  d: path("M17 15C19.209 15 21 16.79 21 19C21 21.21 19.209 23 17 23H15C12.791 23 11 21.21 11 19C11 16.79 12.791 15 15 15H17Z");
}

.wob51cbxh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 18V20H1V18H12ZM23 18V20H20V18H23ZM22 1C22.552 1 23 1.45 23 2V12C23 12.55 22.552 13 22 13H2C1.448 13 1 12.55 1 12V2C1 1.45 1.448 1 2 1H22Z");
}

</style>
