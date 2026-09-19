<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akyrwvbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="akyrwvbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:misuse" /></template>
