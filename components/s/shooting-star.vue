<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq8uafule.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq8uafule"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shooting-star" /></template>
