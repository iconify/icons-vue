<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kij4pmdra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kij4pmdra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:trend-down" /></template>
