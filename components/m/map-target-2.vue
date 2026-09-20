<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjy_hdcyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjy_hdcyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:map-target-2" /></template>
