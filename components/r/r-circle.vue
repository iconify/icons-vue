<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-upa935e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-upa935e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:r-circle" /></template>
