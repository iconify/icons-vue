<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3n_o_sbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="more-horizontal-outline"><path class="Vector w3n_o_sbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:more-horizontal-outline" /></template>
