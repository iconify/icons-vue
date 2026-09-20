<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbcqh3bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mbcqh3bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-pin-outline" /></template>
