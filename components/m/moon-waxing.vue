<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvbu5_bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moon-waxing" /></template>
<style>
.cvbu5_bmu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12M12 2.25q4.038.001 6.892 2.857Q21.747 7.962 21.747 12t-2.855 6.893Q16.038 21.749 12 21.75q-2.327-.002-3.852-3.052Q6.752 15.904 6.752 12t1.396-6.698q1.525-3.05 3.851-3.052z");
}

</style>
