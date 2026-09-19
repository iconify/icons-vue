<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0oy5k6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ln0oy5k6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:qnt" /></template>
