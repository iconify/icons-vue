<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akp-j5wvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="akp-j5wvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:multiple-stars" /></template>
