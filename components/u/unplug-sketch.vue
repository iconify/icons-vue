<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l-pysdxjg.css';
import '../../css/l/lilb5_awy.css';
import '../../css/m/mo4-r3vsv.css';
import '../../css/x/x7twskxam.css';
import '../../css/k/kck-09bwl.css';
import '../../css/o/og3p9brbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l-pysdxjg"/><path class="lilb5_awy wm-k"/><path class="mo4-r3vsv wm-a"/><path class="wm-k x7twskxam"/><path class="kck-09bwl wm-a"/><path class="og3p9brbx wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:unplug-sketch" /></template>
