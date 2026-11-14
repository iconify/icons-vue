<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2yqc4sjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:network" /></template>
<style>
.b2yqc4sjb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-2.75 0-2.75 2.75q0 2.345 2 2.69v2.109q-2.5.351-2.5 3.201q0 .921.261 1.581l-2.69 2.151q-.669-.482-1.821-.482q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75q0-.556-.112-1l2.813-2.25q.774.5 2.049.5t2.049-.5l2.813 2.25q-.112.444-.112 1q0 2.75 2.75 2.75t2.75-2.75t-2.75-2.75q-1.152 0-1.821.482l-2.69-2.151q.261-.66.261-1.581q0-2.85-2.5-3.201V7.19q2-.345 2-2.69q0-2.75-2.75-2.75");
}

</style>
