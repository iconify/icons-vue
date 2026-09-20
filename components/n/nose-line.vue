<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x381b8bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x381b8bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nose-line" /></template>
