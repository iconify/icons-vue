<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4187fbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4187fbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-voice-round" /></template>
