<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc08l--tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dc08l--tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:question-octagon-fill" /></template>
