<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2x01abpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b2x01abpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:pin" /></template>
