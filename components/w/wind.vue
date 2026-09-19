<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj305obcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vj305obcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:wind" /></template>
