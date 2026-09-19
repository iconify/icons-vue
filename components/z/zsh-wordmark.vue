<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jspq0yv0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jspq0yv0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:zsh-wordmark" /></template>
