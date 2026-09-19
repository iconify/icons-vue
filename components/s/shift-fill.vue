<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8yp_sb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e8yp_sb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shift-fill" /></template>
