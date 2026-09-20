<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rnu_vbc4z.css';
import '../../css/p/pj1n6paza.css';
import '../../css/w/w95ndgbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rnu_vbc4z"/><path class="pj1n6paza"/><path class="w95ndgbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-missed-call" /></template>
