<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o--vv303e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":408};
const content = `<path class="o--vv303e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:shopping-basket" /></template>
