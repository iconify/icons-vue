<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9oq_pbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9oq_pbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:shopping-cart" /></template>
