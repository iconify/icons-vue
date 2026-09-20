<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rftvm9l3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rftvm9l3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-horizontal-rotate-counterclockwise" /></template>
