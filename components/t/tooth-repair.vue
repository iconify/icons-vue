<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8uil3bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-repair" /></template>
<style>
.e8uil3bav {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.566 3.192q-.769.34-1.566.885q-3.593-2.459-6.622-.728l-.025.015q-3.372 2.107-1.049 7.915q.628 1.57 1.309 4.91q.395 1.937.659 2.993q.517 2.068 2.103 2.068t2.103-2.068l1-4Q11.523 15 12 15t.522.182l1 4q.517 2.068 2.103 2.068t2.103-2.068q.264-1.056.659-2.993q.681-3.34 1.309-4.91q2.314-5.784-1.021-7.898q-1.999-1.48-4.662-.593q-.038.013-.073.029q-.125.057-.221.154q-.097.097-.153.221");
}

</style>
