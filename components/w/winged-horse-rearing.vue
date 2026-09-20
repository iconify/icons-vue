<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc82gg_se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nc82gg_se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:winged-horse-rearing" /></template>
