<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iecs1vn-f.css';
import '../../css/m/mqlblbcbw.css';
import '../../css/f/f6a0n6n9n.css';
import '../../css/u/u2d2ebb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iecs1vn-f"/><path class="mqlblbcbw wm-a"/><path class="f6a0n6n9n wm-k"/><path class="u2d2ebb7e wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zoom-in-sketch" /></template>
