<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot3vn1bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ot3vn1bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-tickets" /></template>
