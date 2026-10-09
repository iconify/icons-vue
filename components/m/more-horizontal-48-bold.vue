<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j45fmlboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j45fmlboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-horizontal-48-bold" /></template>
