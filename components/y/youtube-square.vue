<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a80mw2isl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a80mw2isl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:youtube-square" /></template>
