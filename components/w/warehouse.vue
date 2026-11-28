<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgdzr_klv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgdzr_klv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:warehouse" /></template>
