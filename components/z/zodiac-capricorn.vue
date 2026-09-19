<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p5r0-w4eu.css';
import '../../css/n/ncu8t5zib.css';
import '../../css/r/rjyn3_b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p5r0-w4eu"/><path class="ncu8t5zib"/><path class="rjyn3_b7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zodiac-capricorn" /></template>
