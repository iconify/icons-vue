<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufl8c1dfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufl8c1dfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:undo" /></template>
