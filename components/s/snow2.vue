<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-jeeccqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-jeeccqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:snow2" /></template>
