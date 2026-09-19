<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwshshvdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zwshshvdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-end-btn-fill" /></template>
