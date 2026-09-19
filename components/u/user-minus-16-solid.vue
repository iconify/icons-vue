<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i29v76buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i29v76buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-minus-16-solid" /></template>
