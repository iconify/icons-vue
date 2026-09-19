<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8e4y6bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="t8e4y6bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:traget" /></template>
