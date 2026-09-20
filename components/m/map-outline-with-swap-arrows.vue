<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw7e6_c3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dw7e6_c3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-outline-with-swap-arrows" /></template>
