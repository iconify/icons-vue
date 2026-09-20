<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js6s8rg9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="js6s8rg9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:replit" /></template>
