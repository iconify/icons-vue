<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6_kfdbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6_kfdbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sun-behind-small-cloud" /></template>
