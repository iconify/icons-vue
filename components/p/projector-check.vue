<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlws5-bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlws5-bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:projector-check" /></template>
