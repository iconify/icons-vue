<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdttmdz4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fdttmdz4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:person-booth" /></template>
