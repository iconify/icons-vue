<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw70mc_dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fw70mc_dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marreta" /></template>
