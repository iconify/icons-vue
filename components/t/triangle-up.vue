<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swi8b0bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="swi8b0bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-up" /></template>
