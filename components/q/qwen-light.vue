<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8j2qnyux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8j2qnyux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qwen-light" /></template>
