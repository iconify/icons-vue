<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4cec1b5g.css';
import '../../css/d/dijuj1icq.css';
import '../../css/n/n7436gv2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="i4cec1b5g"><path class="dijuj1icq"/><path class="n7436gv2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:wifi-low" /></template>
