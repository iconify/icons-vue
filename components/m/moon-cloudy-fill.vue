<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw2aebcvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw2aebcvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-cloudy-fill" /></template>
