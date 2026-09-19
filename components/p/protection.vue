<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/c/ca3oflbdp.css';
import '../../css/g/gx8mphfqp.css';
import '../../css/f/fa3pa8bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="ca3oflbdp"/><path class="gx8mphfqp"/><path class="fa3pa8bch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:protection" /></template>
