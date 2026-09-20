<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjkqr-26p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjkqr-26p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text" /></template>
