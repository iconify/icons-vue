<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zisu_cc5g.css';
import '../../css/i/i8f0698ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zisu_cc5g"/><path class="i8f0698ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-rain-48-bold" /></template>
