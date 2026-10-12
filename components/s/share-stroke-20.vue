<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tso6gqw6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tso6gqw6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:share-stroke-20" /></template>
