<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf8q1_utc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf8q1_utc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-x" /></template>
