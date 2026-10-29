<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p9fzehbgl.css';
import '../../css/s/sssx3w21g.css';
import '../../css/d/d-jm_9bof.css';
import '../../css/i/isp22yuws.css';
import '../../css/w/wtypv6bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p9fzehbgl"/><path class="sssx3w21g wm-k"/><path class="d-jm_9bof wm-k"/><path class="isp22yuws wm-s"/><path class="wm-s wtypv6bbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-off-sketch" /></template>
