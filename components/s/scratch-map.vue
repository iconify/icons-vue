<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obv4mibzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obv4mibzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scratch-map" /></template>
