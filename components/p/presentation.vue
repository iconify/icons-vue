<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4znacmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4znacmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:presentation" /></template>
