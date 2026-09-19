<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp9kysbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qp9kysbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tag-fill-12" /></template>
