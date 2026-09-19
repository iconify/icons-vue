<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhh8yfbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fhh8yfbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suit-heart" /></template>
