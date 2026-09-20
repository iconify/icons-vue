<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp6fmllkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":491,"height":491};
const content = `<path class="hp6fmllkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mermaid-light" /></template>
