<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iadbdwbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iadbdwbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shuffle-2-line" /></template>
