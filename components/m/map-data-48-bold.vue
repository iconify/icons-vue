<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9jxscckh.css';
import '../../css/h/hwk25ejtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r9jxscckh"/><path class="hwk25ejtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-data-48-bold" /></template>
