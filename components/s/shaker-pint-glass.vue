<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk2noib-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wk2noib-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shaker-pint-glass" /></template>
