<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs6v47kig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs6v47kig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ticket-line" /></template>
