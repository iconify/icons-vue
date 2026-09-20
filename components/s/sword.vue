<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geode8baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="geode8baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sword" /></template>
