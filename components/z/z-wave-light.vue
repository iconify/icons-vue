<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjcbap7vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vjcbap7vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:z-wave-light" /></template>
