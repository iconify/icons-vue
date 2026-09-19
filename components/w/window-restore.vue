<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixma8s7gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixma8s7gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:window-restore" /></template>
