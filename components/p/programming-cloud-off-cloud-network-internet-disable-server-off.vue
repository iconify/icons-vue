<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s034ffble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s034ffble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:programming-cloud-off-cloud-network-internet-disable-server-off" /></template>
