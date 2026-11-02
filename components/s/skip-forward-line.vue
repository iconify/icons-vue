<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb07iqb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb07iqb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skip-forward-line" /></template>
