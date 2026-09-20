<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0ojv7nef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ojv7nef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:transfer-outlined" /></template>
