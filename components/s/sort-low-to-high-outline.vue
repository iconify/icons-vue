<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5d79oz8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k5d79oz8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-low-to-high-outline" /></template>
