<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5rurczee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-array" /></template>
<style>
.z5rurczee {
  fill: currentColor;
  d: path("M4 16.827V7.173q0-.489.343-.83Q4.685 6 5.174 6t.83.342q.342.342.342.831v9.654q0 .489-.342.83Q5.66 18 5.172 18t-.83-.342T4 16.827M8.904 18q-.489 0-.831-.342t-.342-.831V7.173q0-.489.342-.83Q8.415 6 8.903 6h6.193q.489 0 .831.342t.342.831v9.654q0 .489-.342.83q-.342.343-.83.343zm8.75-1.173V7.173q0-.489.342-.83Q18.34 6 18.828 6t.83.342t.342.831v9.654q0 .489-.342.83q-.343.343-.832.343t-.83-.342t-.342-.831");
}

</style>
