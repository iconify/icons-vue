<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6dku23de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a6dku23de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-minus-above-water" /></template>
