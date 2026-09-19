<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1euwac9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f1euwac9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:timer" /></template>
