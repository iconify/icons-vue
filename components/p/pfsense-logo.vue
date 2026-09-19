<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv29q5vwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv29q5vwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pfsense-logo" /></template>
