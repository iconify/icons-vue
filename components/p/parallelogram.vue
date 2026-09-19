<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6zi112qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6zi112qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:parallelogram" /></template>
