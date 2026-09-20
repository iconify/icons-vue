<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdx_gpbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hdx_gpbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plant-in-raised-planter" /></template>
