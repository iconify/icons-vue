<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xohs8_ozi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xohs8_ozi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-one" /></template>
