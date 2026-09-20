<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2ser0o3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="k2ser0o3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-stairs-down" /></template>
