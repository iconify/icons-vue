<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeb48f5_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jeb48f5_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pico-sh-light" /></template>
