<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxgl8sb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cxgl8sb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-dribbble" /></template>
