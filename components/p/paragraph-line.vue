<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mswc7wb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mswc7wb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paragraph-line" /></template>
