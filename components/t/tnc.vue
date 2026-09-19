<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls10upb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ls10upb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tnc" /></template>
