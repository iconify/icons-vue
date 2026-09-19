<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4dhmzbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z4dhmzbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xbp" /></template>
