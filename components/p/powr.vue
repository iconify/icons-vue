<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlih9fbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nlih9fbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:powr" /></template>
