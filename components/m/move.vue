<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp1tngb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp1tngb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:move" /></template>
