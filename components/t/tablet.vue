<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh51pcbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="mh51pcbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:tablet" /></template>
