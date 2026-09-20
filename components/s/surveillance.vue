<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofa66e5-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ofa66e5-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:surveillance" /></template>
