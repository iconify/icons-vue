<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h0oi9ihsm.css';
import '../../css/w/ww1pcf4xt.css';
import '../../css/h/hlg2s0jjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h0oi9ihsm"/><path class="ww1pcf4xt"/><path class="hlg2s0jjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-sketch" /></template>
