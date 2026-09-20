<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7c-rze5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y7c-rze5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:signal" /></template>
