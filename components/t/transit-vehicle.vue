<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw8askbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sw8askbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:transit-vehicle" /></template>
