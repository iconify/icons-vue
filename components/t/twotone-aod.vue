<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbiapcr7c"/><path class="ek3-benoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-aod" /></template>
<style>
.ek3-benoy {
  fill: currentColor;
  d: path("M7 21h10v-1H7zM7 3v1h10V3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jbiapcr7c {
  fill: currentColor;
  d: path("M17 1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 21H7v-1h10zm0-3H7V6h10zm0-14H7V3h10zm-9 6h8v1.5H8zm1 3h6v1.5H9z");
}

</style>
