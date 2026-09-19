<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb5p3izax.css';
import '../../css/l/l_i_9sbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="tb5p3izax"/><path class="l_i_9sbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:map" /></template>
