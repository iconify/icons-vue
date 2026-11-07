<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wvj19kbnp.css';
import '../../css/l/lennyzbya.css';
import '../../css/g/g61gfabvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wvj19kbnp"/><path class="lennyzbya"/><path class="g61gfabvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-off-linear" /></template>
