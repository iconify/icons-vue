<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-q5-nbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a-q5-nbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vihara-solid" /></template>
