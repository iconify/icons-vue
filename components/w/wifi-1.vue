<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7b6kccap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l7b6kccap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:wifi-1" /></template>
