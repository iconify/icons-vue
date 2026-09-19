<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfm_h1b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfm_h1b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-question-mark-filled" /></template>
