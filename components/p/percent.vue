<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9fnkierv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="e9fnkierv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:percent" /></template>
