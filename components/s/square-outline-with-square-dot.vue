<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffogxa9fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ffogxa9fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square-outline-with-square-dot" /></template>
