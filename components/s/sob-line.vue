<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf8oqgb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf8oqgb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sob-line" /></template>
