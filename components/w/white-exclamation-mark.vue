<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc8sz1b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mc8sz1b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:white-exclamation-mark" /></template>
