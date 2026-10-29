<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xa_x1dbjv.css';
import '../../css/d/dlhe9xb0h.css';
import '../../css/p/p9ineh26q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xa_x1dbjv"/><path class="dlhe9xb0h wm-k"/><path class="p9ineh26q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:peacock-feather-sketch" /></template>
