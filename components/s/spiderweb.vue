<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chbtt6sws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="chbtt6sws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:spiderweb" /></template>
