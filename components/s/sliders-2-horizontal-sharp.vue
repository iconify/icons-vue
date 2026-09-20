<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gapq62bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gapq62bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-horizontal-sharp" /></template>
