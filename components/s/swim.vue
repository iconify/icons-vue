<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwmlhl6ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fwmlhl6ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:swim" /></template>
