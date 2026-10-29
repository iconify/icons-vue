<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/ftjlt04ey.css';
import '../../css/i/inirm0b4k.css';
import '../../css/p/poqevy83a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ftjlt04ey"/><path class="inirm0b4k wm-k"/><path class="poqevy83a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:skull-sketch" /></template>
