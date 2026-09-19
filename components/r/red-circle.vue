<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz2zpvbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iz2zpvbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:red-circle" /></template>
