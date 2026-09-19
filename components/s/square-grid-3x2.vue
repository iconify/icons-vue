<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy02ujb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uy02ujb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-grid-3x2" /></template>
