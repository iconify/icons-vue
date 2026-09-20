<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjtrot2-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wjtrot2-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:sort-right" /></template>
