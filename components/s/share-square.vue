<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0te34bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="f0te34bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:share-square" /></template>
