<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma2wh1fer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2wh1fer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-dots" /></template>
