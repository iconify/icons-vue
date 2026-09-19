<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa12ghbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wa12ghbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:ruler" /></template>
