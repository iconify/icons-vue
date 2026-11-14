<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emiah_zbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:type-outline" /></template>
<style>
.emiah_zbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.299 3.232l-6.5 17q-.049.13-.049.268q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.115 0 .224-.034t.203-.1q.094-.065.165-.155q.07-.09.11-.198L9.52 17.25h4.96l1.318 3.513q.04.108.11.198t.165.155t.203.1q.109.034.224.034h4q.138 0 .268-.049q.069-.027.131-.066q.063-.04.117-.09q.053-.051.096-.111t.073-.128t.046-.14t.019-.145q.002-.074-.011-.147t-.038-.142l-6.5-17q-.041-.106-.112-.196q-.07-.089-.164-.154q-.094-.064-.202-.098T14 2.75h-4q-.114 0-.223.034q-.108.034-.202.098q-.094.065-.164.154q-.071.09-.112.196m.852 7.867l.27-.733Q10.825 9.264 12 9.264t1.579 1.103l.27.732q.355.964-.233 1.808q-.588.843-1.616.843t-1.616-.843t-.233-1.808");
}

</style>
