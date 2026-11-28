<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roys9q8ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roys9q8ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:navigation-check" /></template>
