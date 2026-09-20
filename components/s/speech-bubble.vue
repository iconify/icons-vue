<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a63_o0bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="a63_o0bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:speech-bubble" /></template>
