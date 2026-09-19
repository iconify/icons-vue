<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn7trv9jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rn7trv9jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:worship-jewish" /></template>
