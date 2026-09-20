<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rml11abxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rml11abxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-down" /></template>
