<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/f/fg7b3kb3a.css';
import '../../css/t/t0m0k5svp.css';
import '../../css/g/gu96anbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="fg7b3kb3a"/><path class="t0m0k5svp"/><path class="gu96anbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:music-note" /></template>
