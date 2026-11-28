<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy7l0bboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cy7l0bboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:star-slash-thin" /></template>
