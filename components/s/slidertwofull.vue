<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1gy8vb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c1gy8vb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:slidertwofull" /></template>
