<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tstl_rxkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tstl_rxkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoke-detector-alert" /></template>
