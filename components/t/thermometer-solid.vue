<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbar7jbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbar7jbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:thermometer-solid" /></template>
