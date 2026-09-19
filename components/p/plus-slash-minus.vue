<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct5x7jbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ct5x7jbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:plus-slash-minus" /></template>
