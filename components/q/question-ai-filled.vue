<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9l99ntrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9l99ntrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:question-ai-filled" /></template>
