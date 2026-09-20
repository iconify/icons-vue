<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2fucvbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2fucvbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reddit" /></template>
