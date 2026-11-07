<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cfukg-luk.css';
import '../../css/t/tylu5nb4d.css';
import '../../css/g/gkiwa1bxg.css';
import '../../css/o/o5oealbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cfukg-luk"/><path class="tylu5nb4d"/><path class="gkiwa1bxg"/><path class="o5oealbwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sd-card-line-duotone" /></template>
