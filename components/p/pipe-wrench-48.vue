<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cppjm0jfh.css';
import '../../css/m/mz0wy9bse.css';
import '../../css/w/wangxwr8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cppjm0jfh"/><path class="mz0wy9bse"/><path class="wangxwr8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-wrench-48" /></template>
