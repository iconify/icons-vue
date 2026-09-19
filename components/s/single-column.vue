<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i15au7b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i15au7b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:single-column" /></template>
