<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc3uyyb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hc3uyyb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:mail" /></template>
