<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miuduccuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="miuduccuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:patch-plus-fill" /></template>
