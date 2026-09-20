<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyw2iybmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cyw2iybmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tabs" /></template>
