<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1h3x_ruo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k1h3x_ruo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pumpkin-under-stardust" /></template>
