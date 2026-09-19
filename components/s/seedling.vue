<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfd4xlzix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qfd4xlzix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:seedling" /></template>
