<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvvlk1fud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mvvlk1fud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:record-vinyl" /></template>
