<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xprej5blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nephrology" /></template>
<style>
.xprej5blp {
  fill: currentColor;
  d: path("M9.808 20.192v-4.56q-.327.274-.699.417t-.801.143q-2.193 0-3.654-1.625q-1.462-1.625-1.462-3.875V9.308q0-2.25 1.462-3.875t3.654-1.625q1.041 0 1.77.728t.73 1.77t-.73 1.771t-1.77.73v2.385q1.038 0 1.769.73t.73 1.77v6.5zm3.384 0v-6.5q0-1.041.73-1.77t1.77-.73V8.808q-1.038 0-1.769-.729t-.73-1.769t.729-1.771t1.77-.731q2.193 0 3.654 1.625q1.462 1.625 1.462 3.875v1.384q0 2.25-1.462 3.875t-3.654 1.625q-.43 0-.801-.143t-.699-.416v4.56z");
}

</style>
