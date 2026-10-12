<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw5-nd-eu.css';
import '../../css/p/pegc-mbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uw5-nd-eu"/><path class="pegc-mbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pill-bottle-20-bold" /></template>
