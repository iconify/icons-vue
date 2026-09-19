<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpk-spksa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jpk-spksa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:slash-16-solid" /></template>
