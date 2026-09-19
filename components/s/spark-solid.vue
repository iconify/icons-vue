<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1t354xgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1t354xgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:spark-solid" /></template>
