<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk-c8jugz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kk-c8jugz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:theta" /></template>
