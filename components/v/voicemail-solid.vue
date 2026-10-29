<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvfkai1wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvfkai1wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:voicemail-solid" /></template>
