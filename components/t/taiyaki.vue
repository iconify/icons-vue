<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc_p_f1dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:taiyaki" /></template>
<style>
.cc_p_f1dx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.329 11.665Q5.686 4.951 14.21 7.78q2.792.708 3.382 2.924q.19-.262.47-.48l.728-.566q1.056-.822 2.258-.234t1.202 1.926v1.3q0 1.338-1.202 1.926t-2.259-.234l-.727-.566q-.28-.218-.47-.48q-.59 2.216-3.382 2.924q-8.524 2.829-11.881-3.885q-.039-.078-.059-.163T2.25 12t.02-.172t.059-.163M7.01 10.25H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 11t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
