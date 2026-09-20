<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7b8aob9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r7b8aob9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:user" /></template>
