<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o80_k_51n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o80_k_51n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sd-card-fill" /></template>
