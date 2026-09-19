<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1b2lsb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o1b2lsb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-end-fill" /></template>
