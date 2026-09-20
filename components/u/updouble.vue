<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_50olhjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o_50olhjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:updouble" /></template>
