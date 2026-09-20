<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhy94eaxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhy94eaxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xmr" /></template>
