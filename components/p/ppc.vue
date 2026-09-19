<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfewowehb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfewowehb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ppc" /></template>
