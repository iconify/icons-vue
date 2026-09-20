<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ookfb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-8,"top":-1};
const content = `<path class="q4ookfb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:torch" /></template>
