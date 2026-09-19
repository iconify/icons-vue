<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyt-qf0tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyt-qf0tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:windows" /></template>
