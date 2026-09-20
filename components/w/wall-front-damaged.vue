<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cswx4ybwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cswx4ybwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:wall-front-damaged" /></template>
