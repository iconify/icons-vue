<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iac76_0qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iac76_0qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-voice-line" /></template>
