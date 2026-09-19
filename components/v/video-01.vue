<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tz_gf3e9g.css';
import '../../css/f/f0gpxfb_w.css';
import '../../css/e/eturhmkap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tz_gf3e9g"/><path class="f0gpxfb_w"/><circle class="eturhmkap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:video-01" /></template>
