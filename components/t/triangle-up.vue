<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6t7b7boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="k6t7b7boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-up" /></template>
