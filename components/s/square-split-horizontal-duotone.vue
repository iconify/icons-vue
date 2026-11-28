<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfm3n-qmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfm3n-qmc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-split-horizontal-duotone" /></template>
