<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te__9_nlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te__9_nlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:snow-flake" /></template>
