<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyb8srbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyb8srbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ticket-filled" /></template>
