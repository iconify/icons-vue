<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6q2r8xhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-off" /></template>
<style>
.g6q2r8xhz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.903 5.075l6.522 6.522q.496-.3.934-.738Q16.75 9.468 16.75 7.5t-1.391-3.359T12 2.75T8.641 4.141q-.438.438-.738.934M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m14.892 18.78l-7.964-7.964q-2.922.207-5.023 1.602Q3.25 17.17 3.25 20q0 1.75 1.75 1.75zm-.309-5.966q.642.508 1.091 1.092z");
}

</style>
