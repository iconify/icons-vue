<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuw8ucyks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xuw8ucyks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:nine-points-connected" /></template>
