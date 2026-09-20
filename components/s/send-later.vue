<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0j3n1bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0j3n1bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:send-later" /></template>
