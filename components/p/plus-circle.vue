<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piynuegax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="piynuegax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:plus-circle" /></template>
