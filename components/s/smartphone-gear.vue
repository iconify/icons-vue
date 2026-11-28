<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_f3h57tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_f3h57tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartphone-gear" /></template>
