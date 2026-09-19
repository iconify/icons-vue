<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m249ygu5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m249ygu5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:price-tag" /></template>
