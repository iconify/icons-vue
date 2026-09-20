<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_1m5nb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o_1m5nb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:spellcheck" /></template>
