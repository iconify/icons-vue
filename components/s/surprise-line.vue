<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4c6iab5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4c6iab5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:surprise-line" /></template>
