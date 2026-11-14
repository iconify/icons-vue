<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj78r0boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smoothie-cup" /></template>
<style>
.fj78r0boc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.723 5.284Q12.381 5.25 12 5.25q-3.289 0-3.693 2.5h7.386q-.295-1.826-2.13-2.318q-.1.045-.209.061q-.108.015-.217-.002q-.108-.016-.208-.063t-.181-.121zm2.026-1.078q2.216.899 2.468 3.575q1.533.218 1.533 1.969q0 1.677-1.406 1.948q.281.592.21 1.301l-.65 6.5q-.225 2.252-2.488 2.251H9.584q-2.263.001-2.488-2.251l-.65-6.5q-.071-.709.21-1.301Q5.25 11.427 5.25 9.75q0-1.751 1.533-1.969Q7.164 3.75 12 3.75q.576 0 1.089.057l1.854-2.059q.049-.055.108-.099t.126-.076t.138-.05t.146-.022q.073-.004.146.007q.074.01.143.035q.07.025.133.062q.064.038.119.088q.111.099.175.234t.072.284t-.042.289t-.15.252z");
}

</style>
