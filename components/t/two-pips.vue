<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik25qgb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ik25qgb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-pips" /></template>
