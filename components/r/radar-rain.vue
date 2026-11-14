<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb_u6cccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:radar-rain" /></template>
<style>
.zb_u6cccy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.112 2.816-7.057q-.047.104-.061.217t.007.225q.021.113.074.214t.134.181l5.75 5.75q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113L5.78 4.72q-.08-.081-.181-.134t-.214-.074q-.112-.02-.225-.007t-.217.061Q7.888 1.75 12 1.75q4.246 0 7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m14.585 5.64q1.377-.688 1.866-2.123q.721-1.711-.31-2.963q-1.055-1.282-2.835-.779q-1.89.479-2.58 2.55q-.744 2.231.858 3.299q.039.026.081.047q1.429.714 2.92-.031");
}

</style>
