<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6830rfmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6830rfmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yahoo" /></template>
