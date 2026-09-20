<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m9lr-xbek.css';
import '../../css/n/n4nddbcfo.css';
import '../../css/g/g8sz4sbjf.css';
import '../../css/d/dkk21mj1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m9lr-xbek"/><path class="n4nddbcfo"/><path class="g8sz4sbjf"/><path class="dkk21mj1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-vibration-linear" /></template>
