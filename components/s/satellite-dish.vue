<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrck99bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrck99bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:satellite-dish" /></template>
