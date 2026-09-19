<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxkoc6b9e.css';
import '../../css/o/o23x06b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxkoc6b9e"/><path class="o23x06b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reply-all" /></template>
