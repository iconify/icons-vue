<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umf1v3cjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="umf1v3cjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-spiral-stairs-round-right" /></template>
