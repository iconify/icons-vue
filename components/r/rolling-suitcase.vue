<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8v1rm3bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8v1rm3bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:rolling-suitcase" /></template>
