<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnwkubctl.css';
import '../../css/z/znrt3ccop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wnwkubctl"/><path class="znrt3ccop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:save-20-bold" /></template>
