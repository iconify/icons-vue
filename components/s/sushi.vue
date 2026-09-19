<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5yw5vult.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a5yw5vult"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sushi" /></template>
