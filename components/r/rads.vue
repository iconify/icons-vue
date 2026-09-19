<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iui6z0b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iui6z0b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rads" /></template>
