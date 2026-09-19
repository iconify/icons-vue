<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpol7oimp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpol7oimp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:shield-x" /></template>
