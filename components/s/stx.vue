<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9uh54bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o9uh54bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:stx" /></template>
