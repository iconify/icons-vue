<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ol1i1obiv.css';
import '../../css/q/q66k1oafp.css';
import '../../css/m/mm9ogz13k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ol1i1obiv"/><path class="q66k1oafp"/><path class="mm9ogz13k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stamp" /></template>
