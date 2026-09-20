<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asprg8bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="asprg8bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:reddit-square" /></template>
