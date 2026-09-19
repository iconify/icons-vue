<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb6ejtbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fb6ejtbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:reflex-wordmark" /></template>
