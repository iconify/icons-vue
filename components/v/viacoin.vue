<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi9e-h2-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fi9e-h2-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:viacoin" /></template>
