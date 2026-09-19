<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr7htobqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="hr7htobqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:phone" /></template>
