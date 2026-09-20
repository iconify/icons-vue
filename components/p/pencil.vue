<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz4cpybds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fz4cpybds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pencil" /></template>
