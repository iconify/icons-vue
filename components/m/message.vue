<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-q4edcor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-q4edcor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message" /></template>
