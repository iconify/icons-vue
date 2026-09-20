<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnru7fbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cnru7fbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:mobile" /></template>
