<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-ul5rahn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d-ul5rahn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:share-boxed" /></template>
