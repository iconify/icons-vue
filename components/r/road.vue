<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz-l9cc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1856,"height":1280};
const content = `<path class="oz-l9cc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:road" /></template>
