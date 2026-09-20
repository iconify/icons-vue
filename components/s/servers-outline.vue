<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4tt-6big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l4tt-6big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:servers-outline" /></template>
