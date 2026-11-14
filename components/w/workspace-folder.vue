<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4zm915qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workspace-folder" /></template>
<style>
.m4zm915qg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.824 10.25h3.5l.606-5.865l-3.507-.526zm5 .073q1.926.376 1.926 2.677v6.5q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75V11q0-2.75 2.75-2.75h.115L4.51 4.623q-.012-.073-.01-.146q.003-.074.019-.146q.017-.072.047-.139q.031-.068.074-.128t.096-.111q.054-.05.117-.089t.132-.066t.142-.038l.012-.002l5-.75q.147-.022.292.014t.265.125t.197.216q.077.128.099.276l.004.034l.68 6.577h1.641l.686-7.32q.007-.074.028-.144q.021-.071.056-.136q.034-.066.081-.123t.103-.105t.122-.082t.136-.057q.071-.021.144-.029t.147-.001l.041.005l5 .75q.071.011.139.035q.067.024.129.06t.116.084t.098.104t.076.12t.052.133t.026.14t-.001.143zM8.5 8.25q.149 0 .287.057t.243.163l1.064 1.064l-.509-4.926l-3.47.521l.52 3.121z");
}

</style>
