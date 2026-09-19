<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnz6y-bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tnz6y-bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:redux" /></template>
