<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n0c1-_gug.css';
import '../../css/e/e8cb6cwzn.css';
import '../../css/a/ani_o8bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n0c1-_gug"/><path class="e8cb6cwzn wm-shadow"/><path class="ani_o8bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plus-engrave" /></template>
