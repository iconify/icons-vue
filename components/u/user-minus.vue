<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to3w6o15e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="to3w6o15e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-minus" /></template>
