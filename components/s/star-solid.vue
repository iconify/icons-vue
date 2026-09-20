<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leypshb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="leypshb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:star-solid" /></template>
