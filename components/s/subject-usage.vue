<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b27kxrbdr.css';
import '../../css/f/f-7sbkbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b27kxrbdr"/><path class="f-7sbkbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subject-usage" /></template>
