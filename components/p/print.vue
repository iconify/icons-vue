<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w33lbnb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="w33lbnb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:print" /></template>
