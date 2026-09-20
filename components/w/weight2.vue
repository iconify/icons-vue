<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k__wu0p8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k__wu0p8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:weight2" /></template>
