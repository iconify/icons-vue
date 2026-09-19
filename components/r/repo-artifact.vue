<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxlaslbqv.css';
import '../../css/f/f-sg0db9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oxlaslbqv"/><path class="f-sg0db9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:repo-artifact" /></template>
