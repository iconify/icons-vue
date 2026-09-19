<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov1lm5bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="ov1lm5bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:search-in-file" /></template>
