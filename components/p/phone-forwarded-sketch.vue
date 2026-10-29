<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v84758bcl.css';
import '../../css/q/qchrgwbbi.css';
import '../../css/r/r-qz_sbwo.css';
import '../../css/h/h1gv6acew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v84758bcl"/><path class="qchrgwbbi wm-s"/><path class="r-qz_sbwo wm-k"/><path class="h1gv6acew wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-forwarded-sketch" /></template>
