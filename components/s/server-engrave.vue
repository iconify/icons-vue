<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/spuqbqsgy.css';
import '../../css/e/e3iia6wxp.css';
import '../../css/g/g8ehjj7yy.css';
import '../../css/k/ksdsltdkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="spuqbqsgy wm-k"/><path class="e3iia6wxp wm-shadow"/><path class="g8ehjj7yy wm-k"/><path class="ksdsltdkn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:server-engrave" /></template>
