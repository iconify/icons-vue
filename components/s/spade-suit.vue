<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibmfn8bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ibmfn8bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:spade-suit" /></template>
