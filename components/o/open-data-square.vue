<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8b5m4b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s8b5m4b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:open-data-square" /></template>
