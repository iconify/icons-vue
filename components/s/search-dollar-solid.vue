<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6h3y_p6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d6h3y_p6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:search-dollar-solid" /></template>
