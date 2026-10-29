<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sqojf1bzw.css';
import '../../css/o/o9zlyg2gf.css';
import '../../css/a/ao21d5blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sqojf1bzw"/><path class="o9zlyg2gf wm-shadow"/><path class="ao21d5blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sidebar-engrave" /></template>
