<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwuams2xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwuams2xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:vib" /></template>
