<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7i4xyzxi"/><path class="hgix6k0rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-punch-clock" /></template>
<style>
.b7i4xyzxi {
  fill: currentColor;
  d: path("M21 6h-3V1H6v5H3v16h18zM8 3h8v3H8zm4 16c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

.hgix6k0rl {
  fill: currentColor;
  d: path("M12.5 11.5h-1v2.71l1.64 1.64l.71-.71l-1.35-1.35z");
}

</style>
