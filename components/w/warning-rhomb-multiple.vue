<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfc6bvtpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfc6bvtpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-rhomb-multiple" /></template>
