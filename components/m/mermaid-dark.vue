<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il7l4tb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":491,"height":491};
const content = `<path class="il7l4tb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mermaid-dark" /></template>
