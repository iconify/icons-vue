<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8r91twaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y8r91twaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:review-warning" /></template>
