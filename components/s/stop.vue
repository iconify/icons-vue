<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2gs1d8kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2gs1d8kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:stop" /></template>
