<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpjyrl2cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mpjyrl2cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:satellite" /></template>
