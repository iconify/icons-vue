<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_mlhb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2_mlhb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:network-gear" /></template>
