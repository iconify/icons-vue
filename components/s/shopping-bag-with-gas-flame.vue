<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc9v1m4ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nc9v1m4ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-gas-flame" /></template>
