<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhdfpcb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rhdfpcb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:numbered-list-16-solid" /></template>
