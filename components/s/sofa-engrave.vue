<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xd4aimb_j.css';
import '../../css/n/n6z362bnb.css';
import '../../css/s/sxuvjhbsh.css';
import '../../css/g/gybz7ebzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xd4aimb_j"/><path class="n6z362bnb wm-shadow"/><path class="sxuvjhbsh"/><path class="gybz7ebzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sofa-engrave" /></template>
