<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/evlh4v6mo.css';
import '../../css/i/ixwphl9ao.css';
import '../../css/l/l4-wf0bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="evlh4v6mo"/><path class="ixwphl9ao"/><path class="l4-wf0bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:pill" /></template>
