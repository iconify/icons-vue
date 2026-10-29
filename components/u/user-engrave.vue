<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nyo9d_2dy.css';
import '../../css/p/pexkecb2t.css';
import '../../css/x/xvkzbpb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nyo9d_2dy"/><path class="pexkecb2t wm-shadow"/><path class="xvkzbpb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-engrave" /></template>
