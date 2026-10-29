<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mey_bqu0u.css';
import '../../css/t/t8w3xju4u.css';
import '../../css/h/h7v3tlb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mey_bqu0u wm-k"/><path class="t8w3xju4u wm-k"/><path class="h7v3tlb3w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:webhook-sketch" /></template>
