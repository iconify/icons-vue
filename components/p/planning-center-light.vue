<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcy09obnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pcy09obnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-light" /></template>
