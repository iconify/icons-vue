<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfyb8iuwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfyb8iuwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rake-line" /></template>
