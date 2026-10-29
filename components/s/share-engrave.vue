<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lzqo3mlvs.css';
import '../../css/a/a09or3byo.css';
import '../../css/p/p7fropb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lzqo3mlvs"/><path class="a09or3byo wm-shadow"/><path class="p7fropb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:share-engrave" /></template>
