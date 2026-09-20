<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrvuy5biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nrvuy5biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unblink-light" /></template>
