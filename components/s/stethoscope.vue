<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sn6ctbueb.css';
import '../../css/i/ia_6o7hbh.css';
import '../../css/l/lo_qdmgth.css';
import '../../css/u/u7ct2xx4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sn6ctbueb"/><path class="ia_6o7hbh"/><path class="lo_qdmgth"/><path class="u7ct2xx4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stethoscope" /></template>
