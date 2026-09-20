<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczd56bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tczd56bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-door-one-way-down" /></template>
