<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko4jtjbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko4jtjbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-badge-line" /></template>
