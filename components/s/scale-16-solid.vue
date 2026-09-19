<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3tc6s50q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m3tc6s50q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:scale-16-solid" /></template>
