<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw5rzgs8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vw5rzgs8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nlg" /></template>
