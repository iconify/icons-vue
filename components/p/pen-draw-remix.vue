<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa8y0ib7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oa8y0ib7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pen-draw-remix" /></template>
