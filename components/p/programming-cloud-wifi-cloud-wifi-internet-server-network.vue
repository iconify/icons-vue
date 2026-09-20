<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjymg8btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cjymg8btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:programming-cloud-wifi-cloud-wifi-internet-server-network" /></template>
