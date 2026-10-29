<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y3rzw4quo.css';
import '../../css/b/bt8z4zwkv.css';
import '../../css/w/w6cbyybob.css';
import '../../css/v/vf78t_b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y3rzw4quo"/><path class="bt8z4zwkv wm-a"/><path class="w6cbyybob wm-k"/><path class="vf78t_b8x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pill-sketch" /></template>
