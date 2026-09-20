<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iac8q5bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iac8q5bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-circle-line" /></template>
