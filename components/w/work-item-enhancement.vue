<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1p0mx41p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v1p0mx41p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-enhancement" /></template>
