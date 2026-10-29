<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cmyeelv4u.css';
import '../../css/o/ohsupcbxt.css';
import '../../css/i/inidtdb2d.css';
import '../../css/a/aulea8_ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cmyeelv4u"/><path class="ohsupcbxt wm-a"/><path class="inidtdb2d wm-k"/><path class="aulea8_ox wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thermometer-snowflake-sketch" /></template>
