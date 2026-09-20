<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha3ajhb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha3ajhb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-plus-outline" /></template>
