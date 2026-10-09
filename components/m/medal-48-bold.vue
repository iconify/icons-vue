<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzhgbf3_i.css';
import '../../css/o/o_os-tbha.css';
import '../../css/y/yk66m8x8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lzhgbf3_i"/><path class="o_os-tbha"/><path class="yk66m8x8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medal-48-bold" /></template>
