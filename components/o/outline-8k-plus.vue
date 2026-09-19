<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifi9bmy0b"/><path class="pljig0b1n"/><path class="quyl-rp3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-8k-plus" /></template>
<style>
.ifi9bmy0b {
  fill: currentColor;
  d: path("M7 15h2c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1m.5-5h1v1.5h-1zm0 2.5h1V14h-1z");
}

.pljig0b1n {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 8.5h-1.5V10h-1v1.5H15v1h1.5V14h1v-1.5H19V19H5V5h14z");
}

.quyl-rp3f {
  fill: currentColor;
  d: path("M12.5 12.75L14.25 15H16l-2.25-3L16 9h-1.75l-1.75 2.25V9H11v6h1.5z");
}

</style>
