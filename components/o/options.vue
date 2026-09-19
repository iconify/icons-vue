<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnccayner.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnccayner"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:options" /></template>
