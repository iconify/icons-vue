<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml63hhbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ml63hhbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:separate-horizontal-16" /></template>
