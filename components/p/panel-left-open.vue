<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/gno__6bnx.css';
import '../../css/n/npbiomb3d.css';
import '../../css/c/cvpr-5bot.css';
import '../../css/o/olay1zo5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="gno__6bnx wm-shadow"/><path class="npbiomb3d wm-shadow"/><path class="cvpr-5bot"/><path class="olay1zo5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:panel-left-open" /></template>
