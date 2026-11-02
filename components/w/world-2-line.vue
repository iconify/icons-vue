<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9u-l8sff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9u-l8sff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:world-2-line" /></template>
