<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3b192omv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p3b192omv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-start" /></template>
