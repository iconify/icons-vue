<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv82mebng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sv82mebng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:phone" /></template>
