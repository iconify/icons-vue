<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb75cm3nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wb75cm3nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:report-16" /></template>
