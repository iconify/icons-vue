<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na2xifbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="na2xifbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:storm" /></template>
