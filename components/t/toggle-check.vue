<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm-a4zent"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toggle-check" /></template>
<style>
.rm-a4zent {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5.75h8q2.589 0 4.419 1.831Q22.25 9.411 22.25 12t-1.831 4.419T16 18.25H8q-2.589 0-4.419-1.831Q1.75 14.589 1.75 12t1.831-4.419Q5.411 5.75 8 5.75M12.25 12q0-3.75 3.75-3.75T19.75 12T16 15.75T12.25 12m1.5 0q0 2.25 2.25 2.25T18.25 12T16 9.75T13.75 12m-6.779.161l-.691-.691q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T5 12t.057.287t.163.243l1.25 1.25q.105.106.243.163T7 14t.287-.057t.243-.163l.027-.028l2.25-2.5q.05-.055.088-.119q.037-.063.062-.133q.025-.069.035-.143t.007-.146q-.004-.074-.022-.146q-.018-.071-.05-.138t-.076-.126t-.099-.108t-.119-.088q-.063-.037-.133-.062q-.069-.025-.143-.035t-.146-.007q-.074.004-.146.022q-.071.018-.138.05t-.126.076t-.108.099z");
}

</style>
