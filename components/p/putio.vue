<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t4e6ys-el.css';
import '../../css/u/uprcssgre.css';
import '../../css/u/urmk4acde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="t4e6ys-el"/><path clip-rule="evenodd" class="uprcssgre"/><path class="urmk4acde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:putio" /></template>
