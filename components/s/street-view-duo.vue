<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rc_3vsnmc.css';
import '../../css/m/mspgd1bzj.css';
import '../../css/n/n72omlbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rc_3vsnmc"/><path class="mspgd1bzj"/><path class="n72omlbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:street-view-duo" /></template>
