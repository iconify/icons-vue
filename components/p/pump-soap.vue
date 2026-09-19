<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgv4y0x0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="wgv4y0x0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pump-soap" /></template>
