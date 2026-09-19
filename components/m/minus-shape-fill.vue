<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duvy2ibrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="duvy2ibrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:minus-shape-fill" /></template>
