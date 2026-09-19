<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyrp0obts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cyrp0obts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:map-pin-plus" /></template>
