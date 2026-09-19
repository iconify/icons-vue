<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a17zhziwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a17zhziwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:markdown" /></template>
