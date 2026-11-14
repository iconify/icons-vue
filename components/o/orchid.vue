<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx5eknbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:orchid" /></template>
<style>
.nx5eknbjt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.563 6.344q-.034.819.115 1.603q-1.332-.71-2.875-.82q-3.551-.254-4.515 2.636q-.073.22-.009.443q.868 3.039 4.418 3.292q.684.049 1.339-.011q-.307.607-.507 1.307q-.885 3.095.82 6.078q.074.13.192.221t.262.131t.292.02q.148-.019.277-.093l.044-.027q2.584-1.723 5.168 0q.061.041.13.069q.068.028.14.043t.147.014q.074 0 .146-.015q.073-.014.141-.042t.129-.07t.114-.093q.052-.053.093-.114l.027-.044q1.705-2.983.82-6.078q-.2-.7-.507-1.307q.655.06 1.339.011q3.55-.253 4.418-3.292q.064-.223-.009-.443q-.964-2.89-4.515-2.636q-1.543.11-2.875.82q.149-.784.115-1.603q-.107-2.575-1.907-4.374q-.105-.106-.243-.163T12 1.75t-.287.057t-.243.163q-1.8 1.799-1.907 4.374");
}

</style>
