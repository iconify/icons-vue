<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgumd2yhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgumd2yhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:north-star-solid" /></template>
