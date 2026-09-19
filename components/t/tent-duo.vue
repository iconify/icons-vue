<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dxa8muzrd.css';
import '../../css/o/olpi3qujl.css';
import '../../css/a/a1myf2bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dxa8muzrd"/><path class="olpi3qujl"/><path class="a1myf2bxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tent-duo" /></template>
