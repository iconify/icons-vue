<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa6as_vez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wa6as_vez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:square" /></template>
