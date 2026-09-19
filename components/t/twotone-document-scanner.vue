<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljs-t7b1h"/><path class="r3gbiob3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-document-scanner" /></template>
<style>
.ljs-t7b1h {
  fill: currentColor;
  d: path("M7 6v12h10V6zm8 10H9v-2h6zm0-3H9v-2h6zm0-3H9V8h6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r3gbiob3v {
  fill: currentColor;
  d: path("M7 3H4v3H2V1h5zm15 3V1h-5v2h3v3zM7 21H4v-3H2v5h5zm13-3v3h-3v2h5v-5zM17 6H7v12h10zm2 12c0 1.1-.9 2-2 2H7c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2zM15 8H9v2h6zm0 3H9v2h6zm0 3H9v2h6z");
}

</style>
