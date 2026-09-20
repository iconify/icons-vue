<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u861_z2tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u861_z2tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:react-table" /></template>
