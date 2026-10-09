<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvxc71wgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cvxc71wgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-off-48-bold" /></template>
