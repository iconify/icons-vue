<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxq8y6y1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rxq8y6y1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pictures" /></template>
