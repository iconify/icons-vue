<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i23y3acgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":432};
const content = `<path class="i23y3acgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:nature" /></template>
