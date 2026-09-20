<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od2094b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="od2094b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:serving-dome" /></template>
