<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywnzoobqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywnzoobqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ranking3-filled" /></template>
