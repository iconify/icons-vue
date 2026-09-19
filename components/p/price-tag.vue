<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oih079b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oih079b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:price-tag" /></template>
