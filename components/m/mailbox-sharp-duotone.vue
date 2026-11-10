<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y4sosteim"/><path clip-rule="evenodd" class="u89gmdbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mailbox-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u89gmdbts {
  fill-rule: evenodd;
  d: path("M7 5C9.209 5 11 6.79 11 9V17H3V9C3 6.79 4.791 5 7 5ZM5 8V10H9V8H5Z");
}

.y4sosteim {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 18C23 18.55 22.552 19 22 19H13V21H11V19H2C1.448 19 1 18.55 1 18V9C1 5.69 3.686 3 7 3H17C20.312 3 23 5.69 23 9V18Z");
}

</style>
