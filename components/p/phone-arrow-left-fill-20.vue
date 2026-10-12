<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2j72gzuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f2j72gzuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-arrow-left-fill-20" /></template>
