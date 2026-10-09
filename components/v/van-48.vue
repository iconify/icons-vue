<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp02g-bms.css';
import '../../css/r/roowebboo.css';
import '../../css/r/rviy4nhfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fp02g-bms"/><path class="roowebboo"/><path class="rviy4nhfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:van-48" /></template>
