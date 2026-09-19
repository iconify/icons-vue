<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/casyzt9mq.css';
import '../../css/g/gu5han_5f.css';
import '../../css/y/ywx-y6bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="casyzt9mq"><path class="gu5han_5f"/><path class="ywx-y6bsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:selected-focus" /></template>
