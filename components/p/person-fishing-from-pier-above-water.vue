<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhezw0uiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mhezw0uiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-fishing-from-pier-above-water" /></template>
