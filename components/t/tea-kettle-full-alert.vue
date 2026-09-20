<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk-19x-6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-19x-6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tea-kettle-full-alert" /></template>
