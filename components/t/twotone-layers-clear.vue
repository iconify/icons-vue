<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud9q6qbkg"/><path class="k518kabnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-layers-clear" /></template>
<style>
.k518kabnn {
  fill: currentColor;
  d: path("M12 4.53L17.74 9l-1.89 1.47l1.43 1.42L21 9l-9-7l-2.59 2.02l1.42 1.42zm9 9.54l-1.63-1.27l-.67.52l1.43 1.43zM3.41.86L2 2.27l4.22 4.22L3 9l9 7l2.1-1.63l1.42 1.42l-3.53 2.75l-7.37-5.73L3 14.07l9 7l4.95-3.85L20.73 21l1.41-1.41zM12 13.47L6.26 9l1.39-1.08l5.02 5.02z");
}

.ud9q6qbkg {
  fill: currentColor;
  d: path("m12 13.47l.67-.53l-5.02-5.02L6.26 9zm0-8.94l-1.17.91l5.02 5.03L17.74 9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
