<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awg3alaya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="awg3alaya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:start" /></template>
