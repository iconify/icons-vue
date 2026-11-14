<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib7vl8bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mountaineering-boot" /></template>
<style>
.ib7vl8bnt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 16.042V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014H12q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.459l3.972 1.325q2.797.808 3.01 4.148q1.518.525 1.518 2.568q0 2.75-2.75 2.75H6q-2.75 0-2.75-2.75q0-1.139.805-1.945q.321-.32.695-.513m6.5-9.096V3.75h-5v4.735zm-5 3.108v5.696h11.958q-.244-2.052-1.914-2.529l-.031-.009l-4.5-1.5q-.056-.019-.108-.046t-.099-.062q-.048-.035-.089-.076q-.041-.042-.075-.089q-.035-.048-.061-.1q-.027-.053-.045-.109q-.018-.055-.027-.113T11.25 11V8.515z");
}

</style>
