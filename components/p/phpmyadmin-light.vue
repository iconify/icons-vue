<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwl8mey3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwl8mey3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpmyadmin-light" /></template>
