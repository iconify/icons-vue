<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcvh03bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hcvh03bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-dancing" /></template>
