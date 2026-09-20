<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlbbh46wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlbbh46wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:nurse-fill" /></template>
