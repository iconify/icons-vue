<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u294-q7gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u294-q7gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wikipedia-w" /></template>
