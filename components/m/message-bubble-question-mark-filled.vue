<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8f_aibnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8f_aibnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-question-mark-filled" /></template>
