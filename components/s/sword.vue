<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-4eaubig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t-4eaubig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sword" /></template>
