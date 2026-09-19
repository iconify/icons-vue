<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lbl9v9c8p.css';
import '../../css/i/i00dwn3uz.css';
import '../../css/c/cunv8wbhl.css';
import '../../css/i/i-x1vnzsf.css';
import '../../css/r/roh-reler.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="lbl9v9c8p"/><path class="i00dwn3uz"/><path class="cunv8wbhl"/><path class="i-x1vnzsf"/><path class="roh-reler"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swatch" /></template>
