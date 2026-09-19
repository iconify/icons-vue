<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npl2v8x7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="npl2v8x7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mitten" /></template>
