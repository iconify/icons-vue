<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyy-xi02y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="nyy-xi02y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:trailer" /></template>
