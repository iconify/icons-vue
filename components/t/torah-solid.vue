<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ox78bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q3ox78bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:torah-solid" /></template>
