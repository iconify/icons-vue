<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akoiqbjnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="akoiqbjnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:mendeley" /></template>
