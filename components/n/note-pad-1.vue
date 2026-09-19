<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/x/xvbk3hb0n.css';
import '../../css/t/tur_nnb9n.css';
import '../../css/m/mygfb2bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="s9cl3zbei"><rect class="xvbk3hb0n"/><path class="tur_nnb9n"/><path class="mygfb2bqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:note-pad-1" /></template>
