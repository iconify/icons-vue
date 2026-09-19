<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce06y8b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ce06y8b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tgch" /></template>
