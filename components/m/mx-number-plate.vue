<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbb36gb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mx-number-plate" /></template>
<style>
.tbb36gb_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5v7q0 4.061 2.845 6.905Q7.939 21.75 12 21.75t6.905-2.845T21.75 12V5q0-2.25-2.25-2.25H17q-2.25 0-2.25 2.25v1.25h-5.5V5q0-2.25-2.25-2.25H4.5Q2.25 2.75 2.25 5m9.748 4.443q.111-.1.252-.15q.14-.05.289-.042t.284.072t.234.175q.093.104.143.233q.05.13.05.269v7.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.816l-1.248 1.123q-.055.05-.119.088q-.063.037-.133.062q-.069.025-.143.035t-.146.007q-.074-.004-.146-.022q-.071-.018-.138-.05t-.126-.076t-.108-.099t-.088-.119q-.037-.063-.062-.133q-.025-.069-.035-.143t-.007-.146q.004-.074.022-.146q.018-.071.05-.138t.076-.126t.099-.108z");
}

</style>
