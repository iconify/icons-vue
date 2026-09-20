<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw4w6t9by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iw4w6t9by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:water" /></template>
