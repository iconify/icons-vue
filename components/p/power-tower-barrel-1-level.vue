<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuy18qpjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kuy18qpjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-barrel-1-level" /></template>
