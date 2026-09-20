<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qodb1q9bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qodb1q9bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-left-click" /></template>
