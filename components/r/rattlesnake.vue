<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmm2wi90d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pmm2wi90d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rattlesnake" /></template>
