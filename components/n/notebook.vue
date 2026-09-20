<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idr_pgb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="idr_pgb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:notebook" /></template>
