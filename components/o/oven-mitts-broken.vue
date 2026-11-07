<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hs6rbmbln.css';
import '../../css/w/w722mfbgk.css';
import '../../css/m/mayyj1h2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hs6rbmbln"/><path class="w722mfbgk"/><path class="mayyj1h2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:oven-mitts-broken" /></template>
