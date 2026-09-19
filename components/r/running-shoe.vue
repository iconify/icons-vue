<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1v9r1bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s1v9r1bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:running-shoe" /></template>
