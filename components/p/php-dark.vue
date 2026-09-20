<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0igmmbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":50,"top":-1};
const content = `<path class="a0igmmbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:php-dark" /></template>
