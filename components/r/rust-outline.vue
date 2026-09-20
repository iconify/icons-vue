<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pso7n1cmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pso7n1cmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rust-outline" /></template>
