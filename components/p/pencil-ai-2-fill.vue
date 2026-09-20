<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcv7r2bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcv7r2bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ai-2-fill" /></template>
