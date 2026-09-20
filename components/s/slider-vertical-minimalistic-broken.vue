<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/ps7dry6or.css';
import '../../css/u/u1ny42dfv.css';
import '../../css/v/vlev-4bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ps7dry6or"/><path class="u1ny42dfv"/><path class="vlev-4bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-vertical-minimalistic-broken" /></template>
