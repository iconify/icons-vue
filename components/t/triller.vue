<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rds309iqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rds309iqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:triller" /></template>
