<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn1sdu5mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nfc-off-outline-sharp" /></template>
<style>
.fn1sdu5mo {
  fill: currentColor;
  d: path("M4 20V5.421L1.887 3.308l.713-.714l19.223 19.223l-.713.714L18.579 20zm4-4V9.421l-3-3V19h12.579l-3-3zm12 1.214l-1-1V5H7.787l-1-1H20zM9 15h4.579L9 10.421zm7-1.786l-1-1V9h-2.5v.714l-.971-.972V8H16zm-2.594-2.62");
}

</style>
