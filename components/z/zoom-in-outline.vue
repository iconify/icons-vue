<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa0cdhdql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wa0cdhdql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:zoom-in-outline" /></template>
