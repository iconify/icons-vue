<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niw28abdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niw28abdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wave-fill" /></template>
