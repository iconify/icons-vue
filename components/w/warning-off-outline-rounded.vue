<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6etfsamf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warning-off-outline-rounded" /></template>
<style>
.r6etfsamf {
  fill: currentColor;
  d: path("M11.566 17.434q-.182-.182-.182-.434t.182-.434t.434-.181t.434.181t.182.434t-.182.434t-.434.181t-.434-.181m-.066-2.55v-3.39l1 1v2.39q0 .214-.143.357t-.357.144t-.357-.144t-.143-.356m.897-9.984q.18.093.305.31l4.546 7.841q.116.214.043.39t-.245.262t-.36.048t-.328-.256L12 6l-.852 1.458q-.134.213-.32.237t-.357-.06t-.244-.274t.062-.403l1.009-1.747q.13-.217.308-.31T12 4.808t.397.093M4.45 19h13.129l-8.31-8.31zm15.479 2.344L18.579 20H4.129q-.46 0-.696-.404q-.237-.404 0-.807L8.55 9.97L2.625 4.046Q2.479 3.9 2.472 3.7t.159-.366t.357-.166t.356.166l17.298 17.304q.146.146.156.344t-.156.363t-.357.165q-.19 0-.356-.165m-6.31-10.55");
}

</style>
