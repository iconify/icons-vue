<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5f_zhbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f5f_zhbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:search-calendar" /></template>
