<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0lj0milb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f0lj0milb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pied-piper" /></template>
