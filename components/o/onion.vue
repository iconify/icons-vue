<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr-m91bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pr-m91bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:onion" /></template>
