<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slvdg_bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slvdg_bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:seven-square-solid" /></template>
