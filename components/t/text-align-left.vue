<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ebu9svp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q-ebu9svp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-align-left" /></template>
