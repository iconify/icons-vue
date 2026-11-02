<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihebkobli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihebkobli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:progress-100-line" /></template>
