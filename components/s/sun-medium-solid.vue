<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dil2jfbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dil2jfbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sun-medium-solid" /></template>
