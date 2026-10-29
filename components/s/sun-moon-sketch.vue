<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kvs9x6woa.css';
import '../../css/u/u9yukr_vq.css';
import '../../css/q/q68_a-bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kvs9x6woa"/><path class="u9yukr_vq wm-k"/><path class="q68_a-bcp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sun-moon-sketch" /></template>
