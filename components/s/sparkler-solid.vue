<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nw5k2pbsn.css';
import '../../css/n/nrtpxxfsi.css';
import '../../css/r/rfiylib8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="nw5k2pbsn"/><path class="nrtpxxfsi wm-a"/><path class="rfiylib8m wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sparkler-solid" /></template>
