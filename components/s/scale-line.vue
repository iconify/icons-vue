<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebqnhrblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebqnhrblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scale-line" /></template>
