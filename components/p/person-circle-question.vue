<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1a-g7buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h1a-g7buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-circle-question" /></template>
