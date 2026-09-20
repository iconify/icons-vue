<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path class="q2dvxtmpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:slcl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.q2dvxtmpb {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.26 15.068l1.11-2.134c-.95-.608-2.613-2.373-1.64-4.542c1.218-2.711 3.565-2.067 4.676-1.671l1.04-2.084c-1.822-.832-5.902-1.507-7.64 2.444c-2.085 4.738 1.066 6.996 2.31 7.885l.143.106zM8.316 19.37l1.062-2.165c1.04.436 3.418.787 4.587-1.28c1.458-2.586-.422-4.15-1.387-4.844L13.64 9.01c1.725 1.022 4.636 4.009 2.49 7.742c-2.578 4.48-6.219 3.187-7.645 2.676z");
}

</style>
