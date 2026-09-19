<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ogpz_dbbw.css';
import '../../css/n/nkh_n2brk.css';
import '../../css/n/nyd6s9b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ogpz_dbbw"/><path class="nkh_n2brk"/><path class="nyd6s9b3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:race-car-duo" /></template>
