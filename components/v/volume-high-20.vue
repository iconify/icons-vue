<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmzaum9qs.css';
import '../../css/p/pefb_hibq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmzaum9qs"/><path class="pefb_hibq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-high-20" /></template>
