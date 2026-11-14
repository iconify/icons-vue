<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni71xvx3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:permille" /></template>
<style>
.ni71xvx3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.876 4.084l-10 15q-.041.061-.069.13q-.028.068-.043.14t-.014.147q0 .074.015.146q.014.073.042.141t.07.129t.093.114q.053.052.114.093q.124.083.27.112t.293-.001q.146-.029.27-.112t.207-.207l10-15q.041-.061.069-.13q.028-.068.043-.14t.014-.147q0-.074-.015-.146q-.014-.073-.042-.141t-.07-.129t-.093-.114q-.053-.052-.114-.093t-.13-.069q-.068-.028-.14-.043t-.147-.014q-.074 0-.146.015q-.073.014-.141.042t-.129.07t-.114.093q-.052.053-.093.114M3 7q0-2.75 2.75-2.75T8.5 7T5.75 9.75T3 7m8.25 7.25Q8.5 14.25 8.5 17t2.75 2.75T14 17t-2.75-2.75m4 2.75q0-2.75 2.75-2.75T20.75 17T18 19.75T15.25 17");
}

</style>
