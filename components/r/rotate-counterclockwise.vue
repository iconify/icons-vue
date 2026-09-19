<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh_0qgpwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uh_0qgpwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate-counterclockwise" /></template>
