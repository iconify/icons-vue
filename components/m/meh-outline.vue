<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/prmctsbee.css';
import '../../css/l/l4qf8vk5b.css';
import '../../css/u/ubpyrdmuc.css';
import '../../css/p/peejenwcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="prmctsbee"/><path clip-rule="evenodd" class="l4qf8vk5b"/><path class="ubpyrdmuc"/><path clip-rule="evenodd" class="peejenwcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:meh-outline" /></template>
