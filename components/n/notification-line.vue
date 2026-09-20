<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8795uznh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8795uznh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-line" /></template>
