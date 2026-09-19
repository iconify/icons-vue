<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8z7hrq8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g8z7hrq8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mp3" /></template>
