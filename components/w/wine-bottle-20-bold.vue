<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olg41hbtg.css';
import '../../css/n/n795oxbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="olg41hbtg"/><path class="n795oxbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-bottle-20-bold" /></template>
