<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9j4cbc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o9j4cbc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:riot" /></template>
