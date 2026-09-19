<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1zioacio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1zioacio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:share-2" /></template>
