<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9gasub-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9gasub-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:markdown-line" /></template>
