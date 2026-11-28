<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao03dfw0g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ksjg_ccnr.css';
import '../../css/r/r66u58wsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao03dfw0g secondary"/><g class="dt0cm9dhy primary"><path class="ksjg_ccnr"/><path class="r66u58wsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ring-duo" /></template>
