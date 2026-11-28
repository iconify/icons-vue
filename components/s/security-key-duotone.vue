<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="im57a6bzz"/><path clip-rule="evenodd" class="vp2egbb1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:security-key-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.im57a6bzz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 16.874C6.2747 16.43 5 14.8639 5 13L5 5C5 2.7908 6.7908 1 9 1L15 1C17.2092 1 19 2.7908 19 5L19 9L19 13C19 14.8639 17.7253 16.43 16 16.874L16 21C16 22.1046 15.1046 23 14 23L10 23C8.8954 23 8 22.1046 8 21Z");
}

.vp2egbb1u {
  fill-rule: evenodd;
  d: path("M19 9L19 13C19 15.2092 17.2092 17 15 17L9 17C6.7908 17 5 15.2092 5 13L5 5C5 2.7908 6.7908 1 9 1L15 1C17.2092 1 19 2.7908 19 5ZM14.1213 11.1213C14.6631 10.5795 15 9.8282 15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C12.8282 12 13.5795 11.6631 14.1213 11.1213ZM12.7071 9.7071C12.8892 9.5251 13 9.2764 13 9C13 8.4477 12.5523 8 12 8C11.4477 8 11 8.4477 11 9C11 9.5523 11.4477 10 12 10C12.2764 10 12.5251 9.8892 12.7071 9.7071Z");
}

</style>
