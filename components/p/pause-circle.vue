<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjco2obit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjco2obit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-circle" /></template>
