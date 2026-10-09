<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgpvo8_dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgpvo8_dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:surf-48" /></template>
