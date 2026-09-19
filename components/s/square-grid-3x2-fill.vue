<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqtq3vidn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="oqtq3vidn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-grid-3x2-fill" /></template>
