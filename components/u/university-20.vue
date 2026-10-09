<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t__07qb8r.css';
import '../../css/z/z7w62dbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t__07qb8r"/><path class="z7w62dbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:university-20" /></template>
