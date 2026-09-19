<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvpnn-2xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dvpnn-2xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:round" /></template>
