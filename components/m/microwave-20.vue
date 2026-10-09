<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_j5rbcgv.css';
import '../../css/x/xw_k98btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v_j5rbcgv"/><path class="xw_k98btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microwave-20" /></template>
