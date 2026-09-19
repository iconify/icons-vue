<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wztm61yks.css';
import '../../css/x/xfuq7vbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wztm61yks"/><path class="xfuq7vbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:railway" /></template>
