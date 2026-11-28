<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx4jzebmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xx4jzebmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:train-track-duotone" /></template>
