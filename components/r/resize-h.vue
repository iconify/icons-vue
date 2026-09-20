<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1_0f7bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a1_0f7bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:resize-h" /></template>
