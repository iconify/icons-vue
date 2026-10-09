<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0377flqh.css';
import '../../css/m/mc3iqybwb.css';
import '../../css/z/zxfgagwie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a0377flqh"/><path class="mc3iqybwb"/><path class="zxfgagwie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pumped-hydro-48" /></template>
