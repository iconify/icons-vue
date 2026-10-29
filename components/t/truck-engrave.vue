<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r2udt_hxm.css';
import '../../css/v/v6vm4shis.css';
import '../../css/u/uqzq5nb1j.css';
import '../../css/n/n255akb9d.css';
import '../../css/w/wjxdsob9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r2udt_hxm wm-k"/><path class="v6vm4shis wm-a"/><path class="uqzq5nb1j wm-shadow"/><path class="n255akb9d wm-k"/><path class="wjxdsob9d wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:truck-engrave" /></template>
