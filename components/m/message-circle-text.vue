<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-w-_16dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-w-_16dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-circle-text" /></template>
