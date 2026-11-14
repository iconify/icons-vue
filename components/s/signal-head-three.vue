<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxu2y6b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:signal-head-three" /></template>
<style>
.jxu2y6b-f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.125 1.25h-.25q-2.123 0-3.624 1.501T6.75 6.375v11.25q0 2.123 1.501 3.624t3.624 1.501h.25q2.123 0 3.624-1.501t1.501-3.624V6.375q0-2.123-1.501-3.624T12.125 1.25m-2.375 5Q9.75 4 12 4t2.25 2.25T12 8.5T9.75 6.25M12 9.75q2.25 0 2.25 2.25T12 14.25T9.75 12T12 9.75m-2.25 8q0-2.25 2.25-2.25t2.25 2.25T12 20t-2.25-2.25");
}

</style>
