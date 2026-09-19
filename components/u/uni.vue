<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-j8aozoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r-j8aozoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:uni" /></template>
