<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a3ytvm-wl"/><path clip-rule="evenodd" class="nt--h2rsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-middle-duotone" /></template>
<style>
.a3ytvm-wl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H18C20.2092 2 22 3.791 22 6V18C22 20.209 20.2092 22 18 22H6C3.7908 22 2 20.209 2 18V6C2 3.791 3.7908 2 6 2H12Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.nt--h2rsr {
  fill-rule: evenodd;
  d: path("M7 9H17C17.5523 9 18 9.448 18 10C18 10.552 17.5523 11 17 11H7C6.4477 11 6 10.552 6 10C6 9.448 6.4477 9 7 9ZM7 13H13C13.5523 13 14 13.448 14 14C14 14.552 13.5523 15 13 15H7C6.4477 15 6 14.552 6 14C6 13.448 6.4477 13 7 13Z");
}

</style>
