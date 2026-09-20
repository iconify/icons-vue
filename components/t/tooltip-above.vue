<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibh-pxvmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ibh-pxvmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-above" /></template>
