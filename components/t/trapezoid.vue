<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0qojsk8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s0qojsk8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:trapezoid" /></template>
