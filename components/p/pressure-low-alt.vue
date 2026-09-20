<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_1etb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n1_1etb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:pressure-low-alt" /></template>
