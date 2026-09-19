<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9xj66b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p9xj66b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-stroke-16" /></template>
