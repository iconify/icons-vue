<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s13_lcbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s13_lcbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:right-down-corner-arrow" /></template>
