<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eov14kbcx"/><path class="e71xpcq7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stop-bold-duotone" /></template>
<style>
.e71xpcq7t {
  fill: currentColor;
  d: path("M3.46484 20.5359C4.92931 22.0004 7.28633 22.0004 12.0004 22.0004C16.7144 22.0004 19.0714 22.0004 20.5359 20.5359C22.0004 19.0714 22.0004 16.7144 22.0004 12.0004C22.0004 7.28633 22.0004 4.92931 20.5359 3.46484L3.46484 20.5359Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.eov14kbcx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355L20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447Z");
}

</style>
