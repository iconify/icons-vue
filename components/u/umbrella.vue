<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ila733bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ila733bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:umbrella" /></template>
