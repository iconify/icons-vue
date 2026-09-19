<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiky2nbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kiky2nbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nlc2" /></template>
