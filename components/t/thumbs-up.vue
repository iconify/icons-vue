<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6cp9b5nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v6cp9b5nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbs-up" /></template>
