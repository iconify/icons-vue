<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u8gkuv4uz.css';
import '../../css/g/gi6x2hbzd.css';
import '../../css/c/cfw654b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u8gkuv4uz"/><path class="gi6x2hbzd"/><path class="cfw654b4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-play-broken" /></template>
