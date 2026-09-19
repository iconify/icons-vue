<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deekjd39l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="deekjd39l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:v8" /></template>
