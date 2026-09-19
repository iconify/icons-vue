<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb3q1erga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="hb3q1erga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:neko-sleep" /></template>
