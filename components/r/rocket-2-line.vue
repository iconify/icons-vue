<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q27ejebhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q27ejebhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rocket-2-line" /></template>
