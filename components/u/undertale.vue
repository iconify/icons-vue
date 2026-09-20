<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e50f1vnnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e50f1vnnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:undertale" /></template>
