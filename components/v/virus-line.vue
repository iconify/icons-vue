<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m00jcezkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m00jcezkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:virus-line" /></template>
