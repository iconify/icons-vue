<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_59ekgyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z_59ekgyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sun-rise" /></template>
