<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tt517txqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-off-28-regular" /></template>
<style>
.tt517txqh {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06L20 21.06v4.19a.75.75 0 0 1-1.166.624L14 22.651l-4.834 3.223A.75.75 0 0 1 8 25.25v-8.73a8.47 8.47 0 0 1-2.5-6.02a8.5 8.5 0 0 1 .658-3.281L2.22 3.28a.75.75 0 0 1 0-1.06M9.5 23.849l4.084-2.723l.098-.055a.75.75 0 0 1 .734.055l4.084 2.723V19.56l-1.22-1.22A8.5 8.5 0 0 1 14 19a8.46 8.46 0 0 1-4.5-1.291zM7.327 8.388A7 7 0 0 0 14 17.5c.736 0 1.444-.118 2.11-.33zM14 2a8.5 8.5 0 0 1 6 14.52v.297l-1.213-1.213a7 7 0 1 0-9.893-9.893l-1.06-1.06A8.48 8.48 0 0 1 14 2");
}

</style>
