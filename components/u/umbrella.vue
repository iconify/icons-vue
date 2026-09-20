<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_j65b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ia_j65b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:umbrella" /></template>
