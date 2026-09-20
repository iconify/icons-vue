<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxlk8fdpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qxlk8fdpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-mode-airplane-server-plane-airplane-disable-wireless-mode-internet-network" /></template>
