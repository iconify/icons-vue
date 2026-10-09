<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hob83lbft.css';
import '../../css/l/lhdxw8u5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hob83lbft"/><path class="lhdxw8u5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tablet-20" /></template>
