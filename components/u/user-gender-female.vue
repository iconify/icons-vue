<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-c3x6kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6-c3x6kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:user-gender-female" /></template>
