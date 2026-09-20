<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duz0nmbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duz0nmbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:max-window-filled" /></template>
