<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygh_3sbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ygh_3sbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-outdated-fill-16" /></template>
