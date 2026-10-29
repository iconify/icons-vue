<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vu1ofi0mn.css';
import '../../css/a/a368k0bcb.css';
import '../../css/g/gjnqlbcln.css';
import '../../css/d/d6roupt_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vu1ofi0mn"/><path class="a368k0bcb wm-a"/><path class="gjnqlbcln wm-k"/><path class="d6roupt_x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microphone-sketch" /></template>
