<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eqfieabcg.css';
import '../../css/f/ff22j4bof.css';
import '../../css/m/mcl7h3lrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eqfieabcg"/><path class="ff22j4bof"/><path class="mcl7h3lrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:structure-check" /></template>
