<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qju7tw8fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qju7tw8fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-direction-left-fill" /></template>
