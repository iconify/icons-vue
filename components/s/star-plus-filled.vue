<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ianewrbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ianewrbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:star-plus-filled" /></template>
