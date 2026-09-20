<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3s-vtbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u3s-vtbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:syrup-jug-with-sugarcane-stalk-with-leaves" /></template>
