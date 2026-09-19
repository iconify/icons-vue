<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvd2vuboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gvd2vuboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:record-circle-fill" /></template>
