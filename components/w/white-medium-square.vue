<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx-hqhb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sx-hqhb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-medium-square" /></template>
