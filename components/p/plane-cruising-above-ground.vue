<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhg3wg2ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nhg3wg2ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-cruising-above-ground" /></template>
