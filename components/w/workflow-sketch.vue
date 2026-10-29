<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rmq984bjk.css';
import '../../css/y/y051bxb0l.css';
import '../../css/f/fjzjs9b3x.css';
import '../../css/p/psa_3hb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rmq984bjk"/><path class="wm-k y051bxb0l"/><path class="fjzjs9b3x wm-k"/><path class="psa_3hb6w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:workflow-sketch" /></template>
