<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r038yv9mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r038yv9mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spartan-helmet" /></template>
