<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqp006-vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqp006-vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-0-warning" /></template>
