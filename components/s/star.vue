<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stogcbbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="stogcbbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:star" /></template>
