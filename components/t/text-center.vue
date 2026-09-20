<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgt9wsb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bgt9wsb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:text-center" /></template>
