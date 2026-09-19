<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgki4y25j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="mgki4y25j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-package" /></template>
