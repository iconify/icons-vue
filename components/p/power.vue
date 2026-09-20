<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t49xjh_fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t49xjh_fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:power" /></template>
