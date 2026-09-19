<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzyzysbgu.css';
import '../../css/w/w5v5asbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzyzysbgu"/><path class="w5v5asbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-question-mark" /></template>
