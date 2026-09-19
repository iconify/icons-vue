<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_v1f4beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z_v1f4beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sort-down" /></template>
