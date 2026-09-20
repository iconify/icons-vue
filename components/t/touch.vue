<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of9ivlzlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="of9ivlzlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:touch" /></template>
