<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx3ofnbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rx3ofnbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:megafone" /></template>
