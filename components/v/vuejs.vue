<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_cb4lblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="k_cb4lblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:vuejs" /></template>
