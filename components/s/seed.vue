<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4tvpbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4tvpbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:seed" /></template>
