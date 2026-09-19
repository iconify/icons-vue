<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n02cxkblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":384};
const content = `<path class="n02cxkblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:time-restore" /></template>
