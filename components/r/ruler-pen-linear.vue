<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oo2qfubvl.css';
import '../../css/q/qu7r9f2pl.css';
import '../../css/c/c9dh15yvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oo2qfubvl"/><path class="qu7r9f2pl"/><path class="c9dh15yvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-pen-linear" /></template>
