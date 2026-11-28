<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uf40w6bvj"/><path clip-rule="evenodd" class="zmksgjbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-bottom-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uf40w6bvj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H18C20.209 2 22 3.791 22 6V18C22 20.209 20.209 22 18 22H6C3.791 22 2 20.209 2 18V6C2 3.791 3.791 2 6 2H12Z");
}

.zmksgjbux {
  fill-rule: evenodd;
  d: path("M7 12H17C17.552 12 18 12.448 18 13C18 13.552 17.552 14 17 14H7C6.448 14 6 13.552 6 13C6 12.448 6.448 12 7 12ZM7 16H13C13.552 16 14 16.448 14 17C14 17.552 13.552 18 13 18H7C6.448 18 6 17.552 6 17C6 16.448 6.448 16 7 16Z");
}

</style>
