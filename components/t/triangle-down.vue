<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2w5s5t3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":392};
const content = `<path class="f2w5s5t3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:triangle-down" /></template>
