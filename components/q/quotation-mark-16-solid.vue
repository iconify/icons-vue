<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdejg98sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdejg98sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:quotation-mark-16-solid" /></template>
