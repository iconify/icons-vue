<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thtc11bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="thtc11bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:thermometer-one" /></template>
