<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd3nyebrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd3nyebrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tiktok-alt" /></template>
