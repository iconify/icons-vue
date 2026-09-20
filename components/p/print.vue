<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrmx5_b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jrmx5_b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:print" /></template>
