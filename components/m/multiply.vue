<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjfiz5icn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zjfiz5icn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:multiply" /></template>
