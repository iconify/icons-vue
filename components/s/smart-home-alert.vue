<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-9m29bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-9m29bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smart-home-alert" /></template>
