<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw2z57h3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rw2z57h3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:unsplash" /></template>
