<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9cc2n58k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="i9cc2n58k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:textheight" /></template>
