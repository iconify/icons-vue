<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur9c4g87e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ur9c4g87e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pencil-ruler" /></template>
