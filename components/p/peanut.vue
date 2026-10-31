<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u578mdyfv.css';
import '../../css/j/jflejabkx.css';
import '../../css/o/oy8ziy8su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u578mdyfv"/><path class="jflejabkx"/><path class="oy8ziy8su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:peanut" /></template>
