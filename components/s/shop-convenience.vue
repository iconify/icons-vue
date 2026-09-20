<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjzs4ac9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qjzs4ac9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:shop-convenience" /></template>
