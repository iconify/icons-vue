<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1aembgqz.css';
import '../../css/t/thhwdjbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c1aembgqz"/><path class="thhwdjbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:qwen" /></template>
