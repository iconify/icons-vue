<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijk7jac2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:surgical-robot" /></template>
<style>
.ijk7jac2w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1.75h16q2.25 0 2.25 2.25T20 6.25H8.75v1.576q1.5.337 1.5 2.174q0 .438-.085.79l3.821 3.217q.503-.257 1.264-.257q2.25 0 2.25 2.25q0 1.837-1.5 2.174v1.076l1.35 1.8q.044.059.076.126q.032.066.051.138q.018.071.022.145t-.007.147t-.034.143q-.025.07-.063.133q-.037.064-.087.119t-.108.099q-.059.044-.126.076q-.066.032-.138.051q-.071.018-.145.022t-.147-.007t-.143-.034q-.07-.025-.133-.063q-.064-.037-.119-.087t-.099-.108l-.9-1.2l-.9 1.2q-.09.119-.218.195t-.276.097t-.292-.015t-.264-.127q-.059-.044-.108-.099q-.05-.055-.087-.119q-.038-.063-.063-.133q-.024-.07-.034-.143t-.007-.147t.022-.145t.051-.138t.076-.126l1.35-1.8v-1.076Q13 17.837 13 16q0-.438.085-.79l-3.821-3.217q-.503.257-1.264.257q-2.25 0-2.25-2.25q0-1.837 1.5-2.174V6.25H4Q1.75 6.25 1.75 4T4 1.75");
}

</style>
