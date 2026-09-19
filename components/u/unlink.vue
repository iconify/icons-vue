<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3awiw91z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v3awiw91z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unlink" /></template>
