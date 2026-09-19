<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr7uqc0zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nr7uqc0zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:trophy-16-solid" /></template>
