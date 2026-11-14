<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcq0_ztqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prompt-edit" /></template>
<style>
.lcq0_ztqg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5.5q0-1.346.952-2.298T5 2.25h12q3.25 0 3.25 3.25v5.611q-1.403-.146-2.841 1.156q-.038.033-.073.069l-3.414 3.414h-3.64l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5q-3.25 0-3.25-3.25zm11 16V19q0-.149.057-.287t.163-.243l5.25-5.25q.013-.014.027-.026q1.777-1.608 3.472.087t.087 3.472q-.012.014-.026.027l-5.25 5.25q-.105.106-.243.163T16 22.25h-2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m2.939-.75l5.016-5.016q.633-.713-.047-1.392q-.679-.68-1.392-.047l-5.016 5.016v1.439z");
}

</style>
