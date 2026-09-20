<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irfjh1x1u.css';
import '../../css/y/y0k_xop1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="irfjh1x1u"/><path class="y0k_xop1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:picture" /></template>
