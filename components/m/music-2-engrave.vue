<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/di8dd7b4y.css';
import '../../css/r/rwxzb1bkv.css';
import '../../css/x/x3bxksq_t.css';
import '../../css/d/dfmjv0mrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="di8dd7b4y"/><path class="rwxzb1bkv wm-shadow"/><path class="x3bxksq_t"/><path class="dfmjv0mrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:music-2-engrave" /></template>
