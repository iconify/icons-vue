<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjm4s4brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjm4s4brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sms" /></template>
