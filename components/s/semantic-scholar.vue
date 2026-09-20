<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwaudvbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hwaudvbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:semantic-scholar" /></template>
