<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v85x-3b_x.css';
import '../../css/j/jnl-9dcly.css';
import '../../css/r/rgyvxub6w.css';
import '../../css/a/apows5dpr.css';
import '../../css/x/xzmjggb6m.css';
import '../../css/i/i6h333bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v85x-3b_x wm-k"/><path class="jnl-9dcly wm-a"/><path class="rgyvxub6w wm-s"/><path class="apows5dpr wm-k"/><path class="wm-a xzmjggb6m"/><path class="i6h333bov wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microphone-off-sketch" /></template>
