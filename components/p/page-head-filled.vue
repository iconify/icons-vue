<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioer6yhnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioer6yhnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:page-head-filled" /></template>
