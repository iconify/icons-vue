<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-6o88bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-6o88bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:me-outlined" /></template>
