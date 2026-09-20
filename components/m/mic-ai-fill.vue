<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9yhz8bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9yhz8bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-ai-fill" /></template>
