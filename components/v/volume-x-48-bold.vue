<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgv66ypwa.css';
import '../../css/t/tzy1k5bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgv66ypwa"/><path class="tzy1k5bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-x-48-bold" /></template>
