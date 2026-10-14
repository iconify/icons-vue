<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci2nsc7wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ci2nsc7wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mysterium-node-dark" /></template>
