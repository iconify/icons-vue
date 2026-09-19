<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0phu2bbs.css';
import '../../css/s/sb6pk9_pi.css';
import '../../css/i/ipe253n2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><rect class="sb6pk9_pi"/><path class="ipe253n2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:microphone-bold" /></template>
