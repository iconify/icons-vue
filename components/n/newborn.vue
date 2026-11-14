<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk0xdupis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:newborn" /></template>
<style>
.fk0xdupis {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.332 2.71q2.722 1.269 3.749 4.091t-.242 5.544l-2.536 5.438q-1.269 2.722-4.091 3.749t-5.544-.242t-3.749-4.091t.242-5.544l2.536-5.438q1.269-2.722 4.091-3.749t5.544.242M10.25 4.25Q6.5 4.25 6.5 8t3.75 3.75q1.553 0 2.652-1.098Q14 9.553 14 8t-1.098-2.652Q11.803 4.25 10.25 4.25m6.03 12.22q-3.658-3.659-8.427-2.705q-.073.014-.141.042t-.129.07q-.062.041-.114.093q-.052.053-.093.114t-.069.13q-.028.068-.043.14t-.014.147q0 .074.015.146q.014.073.042.141t.07.129t.093.114q.053.052.114.093t.13.069q.068.028.14.043t.147.014t.146-.015q3.981-.796 7.073 2.295q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141T16.5 17q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113");
}

</style>
