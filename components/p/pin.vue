<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou2f5gbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ou2f5gbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:pin" /></template>
