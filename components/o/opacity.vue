<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um0rcfaau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="um0rcfaau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:opacity" /></template>
