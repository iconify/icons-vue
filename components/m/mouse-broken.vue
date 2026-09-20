<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dpfspg3tv.css';
import '../../css/i/i5p1eqb6p.css';
import '../../css/g/glahfmzew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dpfspg3tv"/><path class="i5p1eqb6p"/><path class="glahfmzew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mouse-broken" /></template>
