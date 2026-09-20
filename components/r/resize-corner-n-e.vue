<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-7ky8bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="s-7ky8bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:resize-corner-n-e" /></template>
