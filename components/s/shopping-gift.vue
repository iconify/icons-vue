<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhnsj164s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fhnsj164s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-gift" /></template>
