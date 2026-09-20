<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqvyd9bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqvyd9bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:project-arrow-right" /></template>
