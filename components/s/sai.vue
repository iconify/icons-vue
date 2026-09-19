<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq2-meouw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fq2-meouw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sai" /></template>
