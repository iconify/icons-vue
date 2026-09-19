<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7j58ebcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u7j58ebcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-backward-circle-fill" /></template>
