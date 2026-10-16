<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kws3gabmt.css';
import '../../css/h/hjb9uvnoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kws3gabmt"/><path class="hjb9uvnoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waypoints-48" /></template>
