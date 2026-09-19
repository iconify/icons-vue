<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvilx1q3c.css';
import '../../css/h/hmhhaybex.css';
import '../../css/a/a3gl68bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="hmhhaybex"/><path class="a3gl68bbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:phone-video-call" /></template>
