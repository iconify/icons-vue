<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anj8b-evo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anj8b-evo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vernemq-light" /></template>
