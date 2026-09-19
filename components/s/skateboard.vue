<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj5j8p_9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sj5j8p_9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:skateboard" /></template>
