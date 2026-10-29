<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/szgntebkh.css';
import '../../css/j/j58s40qqs.css';
import '../../css/g/g36yryw5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="szgntebkh wm-a"/><path class="j58s40qqs wm-k"/><path class="g36yryw5e wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:radio-sketch" /></template>
