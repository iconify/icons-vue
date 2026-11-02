<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fltz9vbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fltz9vbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paper-line" /></template>
