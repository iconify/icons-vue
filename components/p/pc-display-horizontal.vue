<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ccybcno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z9ccybcno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pc-display-horizontal" /></template>
