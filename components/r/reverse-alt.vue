<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk-6hydha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="sk-6hydha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:reverse-alt" /></template>
