<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlk0frbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zlk0frbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:trade-mark" /></template>
