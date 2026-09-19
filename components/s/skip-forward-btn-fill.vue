<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d93kgmbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d93kgmbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-forward-btn-fill" /></template>
