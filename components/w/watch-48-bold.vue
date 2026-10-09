<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nowsdr-3b.css';
import '../../css/x/xaxgc568e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nowsdr-3b"/><path class="xaxgc568e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:watch-48-bold" /></template>
