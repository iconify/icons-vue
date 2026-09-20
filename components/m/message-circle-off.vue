<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw4l773-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw4l773-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-off" /></template>
