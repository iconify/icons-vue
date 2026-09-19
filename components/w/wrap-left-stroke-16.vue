<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_b-7fbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o_b-7fbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-left-stroke-16" /></template>
