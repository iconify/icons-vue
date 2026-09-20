<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhzx4obkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhzx4obkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sms-failed-outline" /></template>
