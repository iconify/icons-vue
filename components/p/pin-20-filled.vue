<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="myr0rk1uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pin-20-filled" /></template>
<style>
.myr0rk1uh {
  fill: currentColor;
  d: path("M13.325 2.617a2 2 0 0 0-3.203.52l-1.73 3.459a1.5 1.5 0 0 1-.784.721l-3.59 1.436a1 1 0 0 0-.335 1.636L6.293 13L3 16.292V17h.707L7 13.706l2.61 2.61a1 1 0 0 0 1.636-.335l1.436-3.59a1.5 1.5 0 0 1 .722-.784l3.458-1.73a2 2 0 0 0 .52-3.203z");
}

</style>
