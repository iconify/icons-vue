<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5_f4-b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5_f4-b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:thermometer-sun-solid" /></template>
