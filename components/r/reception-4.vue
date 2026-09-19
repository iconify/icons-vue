<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry30_kgre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ry30_kgre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:reception-4" /></template>
