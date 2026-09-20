<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg-4g4b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tg-4g4b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-abnormal-outline" /></template>
