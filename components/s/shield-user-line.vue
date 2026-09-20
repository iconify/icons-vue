<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs3x60bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs3x60bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-user-line" /></template>
