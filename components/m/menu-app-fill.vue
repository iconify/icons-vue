<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol_k1ab-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ol_k1ab-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:menu-app-fill" /></template>
