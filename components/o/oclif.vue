<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rra9mob5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rra9mob5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:oclif" /></template>
