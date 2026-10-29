<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4y95eb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4y95eb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-text" /></template>
