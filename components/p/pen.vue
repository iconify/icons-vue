<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh6k4491x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-3};
const content = `<path class="wh6k4491x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pen" /></template>
