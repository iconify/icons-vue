<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_hd3sfas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o_hd3sfas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:thumbsup" /></template>
