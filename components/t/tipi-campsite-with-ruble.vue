<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5cjwcc9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v5cjwcc9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsite-with-ruble" /></template>
