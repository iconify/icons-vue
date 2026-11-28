<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxp4mbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxp4mbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-arrow-down" /></template>
