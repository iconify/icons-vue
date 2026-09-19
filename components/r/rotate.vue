<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah44nkblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ah44nkblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate" /></template>
