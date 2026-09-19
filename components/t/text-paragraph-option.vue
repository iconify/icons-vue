<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9r-seisg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a9r-seisg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:text-paragraph-option" /></template>
