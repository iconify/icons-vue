<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9f-ncbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9f-ncbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-date" /></template>
