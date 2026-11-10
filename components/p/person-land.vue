<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7uabdf7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f7uabdf7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:person-land" /></template>
