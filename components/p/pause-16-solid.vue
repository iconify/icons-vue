<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwg57p2gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cwg57p2gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pause-16-solid" /></template>
