<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/w/ws63a0bby.css';
import '../../css/s/stdaf0bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="ws63a0bby"/><path class="stdaf0bdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:package-dimension" /></template>
