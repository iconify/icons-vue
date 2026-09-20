<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2zhscb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2zhscb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-fill" /></template>
