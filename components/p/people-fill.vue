<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_5ugmecr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o_5ugmecr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:people-fill" /></template>
