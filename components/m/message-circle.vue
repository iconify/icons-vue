<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy4nunbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy4nunbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-circle" /></template>
