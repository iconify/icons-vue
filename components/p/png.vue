<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c44cj2bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c44cj2bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:png" /></template>
