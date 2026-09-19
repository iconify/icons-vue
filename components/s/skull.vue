<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0_97tc8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="a0_97tc8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:skull" /></template>
