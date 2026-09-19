<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq2_p6b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sq2_p6b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:soc" /></template>
