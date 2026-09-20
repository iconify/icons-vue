<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq8nxtbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sq8nxtbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:snowflake" /></template>
