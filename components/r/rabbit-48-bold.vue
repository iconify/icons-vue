<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_os-tbha.css';
import '../../css/g/g48181t2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_os-tbha"/><path class="g48181t2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rabbit-48-bold" /></template>
