<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pq26m6iud.css';
import '../../css/m/ml0cb1b5h.css';
import '../../css/r/r1l_in_mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pq26m6iud"/><path class="ml0cb1b5h"/><path class="r1l_in_mz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-broken" /></template>
