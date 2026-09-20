<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3w_wnbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c3w_wnbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-solid" /></template>
