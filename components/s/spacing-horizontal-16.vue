<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meyjvcahw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="meyjvcahw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:spacing-horizontal-16" /></template>
