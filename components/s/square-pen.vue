<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlu0ygy0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xlu0ygy0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-pen" /></template>
