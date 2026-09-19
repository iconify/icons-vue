<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbff0lbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qbff0lbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:mindmap-list" /></template>
