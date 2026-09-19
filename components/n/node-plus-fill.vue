<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu640dmwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mu640dmwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:node-plus-fill" /></template>
