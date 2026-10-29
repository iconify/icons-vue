<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p1ms0ib3o.css';
import '../../css/y/ynjdmqhwg.css';
import '../../css/y/y5h00ybfd.css';
import '../../css/x/x3hf-5b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p1ms0ib3o wm-k"/><path class="wm-k ynjdmqhwg"/><path class="wm-s y5h00ybfd"/><path class="wm-s x3hf-5b-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-off-sketch" /></template>
