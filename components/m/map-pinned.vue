<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zqrrajf2c.css';
import '../../css/f/fjo6rmbxh.css';
import '../../css/g/gqchk_boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zqrrajf2c"/><path class="fjo6rmbxh"/><path class="gqchk_boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:map-pinned" /></template>
