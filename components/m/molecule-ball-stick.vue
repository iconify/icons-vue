<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7opc1l_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:molecule-ball-stick" /></template>
<style>
.x7opc1l_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.75q-3.75 0-3.75 3.75q0 1.47.576 2.363l-1.283 1.284Q6.72 11.75 5.5 11.75q-3.75 0-3.75 3.75t3.75 3.75t3.75-3.75q0-1.47-.576-2.363l1.283-1.284q.823.397 2.043.397t2.043-.397l1.283 1.284q-.576.893-.576 2.363q0 3.75 3.75 3.75t3.75-3.75t-3.75-3.75q-1.22 0-2.043.397l-1.283-1.284q.576-.893.576-2.363q0-3.75-3.75-3.75");
}

</style>
