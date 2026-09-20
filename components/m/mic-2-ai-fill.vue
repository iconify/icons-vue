<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie_oe4beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie_oe4beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-2-ai-fill" /></template>
