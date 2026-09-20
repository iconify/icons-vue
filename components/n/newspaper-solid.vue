<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbn7s3nsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vbn7s3nsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:newspaper-solid" /></template>
