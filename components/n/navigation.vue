<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgmv7_r9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:navigation" /></template>
<style>
.qgmv7_r9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.312 6.644l3.847 9.343q.579 1.409-.565 2.414t-2.466.25l-2.632-1.504q-.496-.283-.992 0l-2.632 1.504q-1.322.756-2.466-.25q-1.144-1.005-.565-2.413l3.847-9.344Q10.326 5.097 12 5.097t2.311 1.547z");
}

</style>
