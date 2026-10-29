<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w51c1j92o.css';
import '../../css/f/f460cp0ja.css';
import '../../css/o/o21xwxcop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w51c1j92o wm-a"/><path class="f460cp0ja wm-k"/><path class="o21xwxcop wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tv-sketch" /></template>
