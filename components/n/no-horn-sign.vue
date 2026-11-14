<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sviafrbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:no-horn-sign" /></template>
<style>
.sviafrbda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.5 12q-.001 4.35 3.074 7.427Q7.65 22.503 12 22.503t7.426-3.076T22.5 12q.002-4.35-3.074-7.427T12 1.497T4.574 4.573Q1.499 7.65 1.5 12m8.494-.25q.006.122.006.25t-.006.25H12q.208 0 .386.107l3.864 2.318v-5.35l-3.864 2.318q-.178.107-.386.107zm-.427 2q-.659 1-2.317 1q-2.75 0-2.75-2.75t2.75-2.75q1.658 0 2.317 1h2.225l4.822-2.893q.063-.038.133-.063t.143-.036t.146-.007q.074.003.146.021t.138.05q.067.031.126.075q.06.044.109.099q.05.055.088.118q.107.178.107.386v8q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.208 0-.386-.107l-4.822-2.893z");
}

</style>
