<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7tneubkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u7tneubkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square" /></template>
