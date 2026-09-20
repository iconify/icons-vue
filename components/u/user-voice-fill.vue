<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8d8c1pjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8d8c1pjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-voice-fill" /></template>
