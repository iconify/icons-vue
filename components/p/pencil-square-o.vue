<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb0yldbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="fb0yldbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pencil-square-o" /></template>
