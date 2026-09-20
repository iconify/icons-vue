<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx5d-bc1s.css';
import '../../css/h/hd70nsb5x.css';
import '../../css/u/u2hv0zbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nx5d-bc1s"><path class="hd70nsb5x"/><path class="u2hv0zbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:model-context-protocol-dark" /></template>
