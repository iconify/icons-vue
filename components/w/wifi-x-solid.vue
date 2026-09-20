<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwm4jrbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwm4jrbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wifi-x-solid" /></template>
