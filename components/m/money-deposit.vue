<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blwbkzb0w.css';
import '../../css/r/rh4s4ac8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blwbkzb0w"/><path class="rh4s4ac8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:money-deposit" /></template>
