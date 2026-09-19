<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb9sa7noz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bb9sa7noz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:movement" /></template>
