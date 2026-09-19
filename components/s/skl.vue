<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjj1zg-jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjj1zg-jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:skl" /></template>
