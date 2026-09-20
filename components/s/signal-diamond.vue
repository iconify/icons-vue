<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5v2hhuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5v2hhuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-diamond" /></template>
