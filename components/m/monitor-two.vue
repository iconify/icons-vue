<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjo891b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjo891b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:monitor-two" /></template>
