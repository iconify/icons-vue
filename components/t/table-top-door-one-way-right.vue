<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z66fxfbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="z66fxfbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-door-one-way-right" /></template>
