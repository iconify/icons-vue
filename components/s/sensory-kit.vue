<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktqxibb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sensory-kit" /></template>
<style>
.ktqxibb6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 6.25h.875q2.123 0 3.624 1.501t1.501 3.624v4.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 15.625v-4.25q0-2.123 1.501-3.624T6.875 6.25h.875V5q0-2.25 2.25-2.25h4q.932 0 1.591.659T16.25 5zm-7 0V5q0-.75.75-.75h4q.75 0 .75.75v1.25zm3.28 6.72q-3.53-3.531-7.06 0q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094Q7.811 12.75 9 12.75t2.47 1.28q3.53 3.531 7.06 0q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 12.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-1.281 1.28-2.47 1.28t-2.47-1.28");
}

</style>
