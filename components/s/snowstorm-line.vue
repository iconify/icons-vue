<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt3x90b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt3x90b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowstorm-line" /></template>
