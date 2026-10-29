<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bqphnvzqd.css';
import '../../css/w/w3f2bfw-w.css';
import '../../css/b/bwmm-dbfo.css';
import '../../css/t/tsfppkblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bqphnvzqd"/><path class="w3f2bfw-w wm-a"/><path class="bwmm-dbfo wm-k"/><path class="tsfppkblp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mouse-sketch" /></template>
