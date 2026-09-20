<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szs_rdb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="szs_rdb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-spiral-stairs-round-left" /></template>
