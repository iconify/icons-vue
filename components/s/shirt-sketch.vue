<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b9_wl1bge.css';
import '../../css/u/un2hhabcu.css';
import '../../css/i/i_ysa44lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b9_wl1bge"/><path class="un2hhabcu"/><path class="i_ysa44lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shirt-sketch" /></template>
