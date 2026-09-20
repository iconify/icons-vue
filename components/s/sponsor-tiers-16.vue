<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dht-ux8xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dht-ux8xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sponsor-tiers-16" /></template>
