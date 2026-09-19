<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1iipibae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":712};
const content = `<path class="h1iipibae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sepia" /></template>
